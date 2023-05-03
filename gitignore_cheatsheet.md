

PATTERN     EXPLANATIONS                                EXAMPLES
                                                        .

name    	All name files, name folders, and           /name.log
            files and folders in any name folder        /name/file.txt
                                                        /name/file.txt

name/       Ending with / specifies the pattern is for   /name/file.txt
             a folder.                                   /name/log/name.log
             Matches all files and folders in any        
             name folder                                 no match:
                                                        /name.log

name.file   All files with the name.file                /name.file
                                                        /lib/name.file
