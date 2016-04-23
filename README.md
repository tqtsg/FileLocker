# FileLocker

The FileLocker is a windows command line tool to lock a file.
The lock is a read/write/delete lock.
The lock will be released once you kill the program or after a specified time / keypress.

## Usage:
```
FileLocker [/T LockTime] [/I] [/K] [/Q] file [file...]
```
| Options | Descriptions  |
| :--- | :--- |
| /T | LockTime Time in milliseconds to lock the file |
| /I | Infinite locking until process is killed (default) |
| /K | Lock file until key is pressed | | /Q | Be quiet. |

## License
@Jens Scheffler

http://www.jensscheffler.de/filelocker
