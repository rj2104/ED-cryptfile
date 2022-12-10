## ED-cryptfile
ED-cryptfile is a command line utility to encrypt or decrypt the file with AES256.

##USAGE(file):

####To encrypt the file
cryptfile -e <filename>
Above command will generate a .enc file with is encrypted with password

####To decrypt the file
cryptfile -d <filename>.enc

####To remove original file after any operation
cryptfile -d <filename>.enc -r
