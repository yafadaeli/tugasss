jawab = 'y'
while(jawab == 'y') :
    no = input("no:1 ")
    nama = input("nama:Yafao Zisokhi Daeli ")
    nim = input("nim:311710379 ")
    tugas = float(input("tugas:70 "))
    uts = float(input("uts:65 "))
    uas = float(input("uas:80 "))
    nakhir = (tugas*30/100+uts*35/100+uas*35/100)
    print (nakhir)
    jawab = input("tambah data (y/t): ")
if(jawab == 't') :
    print ("+--------------------------------------------------------+")
    print ("| No |  Nama  |  Nim  |  Tugas  |  Uts  |  Uas  |  nakhir |")
    print ("+--------------------------------------------------------+")
    print ("|",no,"|",nama,"|",nim,"|",tugas,"|",uts,"|",uas,"|",nakhir,"|")
    
