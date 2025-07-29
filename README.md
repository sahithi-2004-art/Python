# Python
# files handling,exception handling
# files
  1.ascii abc-979867
  2.binary
# paths
# opening-userdefined=open(filename,mode of the file)
  *r-reading the data of the file
  *w-writing the data in the file
  *a-append
# closing
# reading
# writin
# appending

# read,write,append file
f=open('smile.txt','a')
f.write("gorgeous......")
f.close()
f=open('smile.txt','w')
f.write("Amazingg......")
f.close()
f=open('smile.txt','a')
f.write("gorgeous......")
f.close()

# Extensions
-->r+ -> file should exist/overwrites existing content
-->w+ -> content clarity(refresh) 
-->a+ -> creates a file if exists, reading works only after seek()
truncate() -> removing the unwanted data
