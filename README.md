# xs-deploy

> Bash script to upload and synchronize Xybersolve's static webite on S3.

#### deploy

```sh

Script: deploy
Purpose: Upload & sync xybersolve static S3 website
Usage: deploy [options]
Options:
  --help:  help and usage
  --version: show version info

  --sync<=directory>: Synchronize files between project and S3
  --upload: Upload all pertinent site files and directories
  --updoad-file=<file>: TODO
  --upload-dir=<directory>: Upload a given directory
  --upload-resume: Upload newest resume
  --upload-letter: Upload newest cover letter
  --delete-file=<file>: TODO
  --delete-dir=<directory>: Delete a directory
  --delete-all: Delete all content
  --delete-logs: Delete all logs
  --remove-log: Remove the log bucket
  --list: List all the content
  --size: show sizes

```

## [License](LICENSE.md)
