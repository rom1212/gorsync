# gorsync
Fast and Safte Rsync in Golang
* Safe: 
  * never override a file
  * never delete a file
  * use flag to specify source and destination, so that we don't mess up with source and destination.
  * dryrun to report what files are to be copied/synced.
* Fast
  * File name and size only.
  * Time stamp probably not matter
