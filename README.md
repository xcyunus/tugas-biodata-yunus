# tugas-biodata-yunus
nik = "61070xxxx"
ttl = "minso,07-11-2002"
jeniskel = "Laki-laki"
golongandarah= "-"
nama = "yunus"
alamat = """bumi,
       RT/RW     :  1.025957 d, 24ʰ 37ᵐ 22.7ˢ
       Kel/Desa  :  sango
       Kecamatan :  0.636 (0.4–0.87) kPa, 0.00628 atm"""
agama = "Kristen"
kewarga = "WNM"
berlaku = "Seumur Hidup"
kerja = "Mahasiswa"
menikah =False
#cetak
print("=============================================================")

print("NIK : ", nik)

print("Nama             : ", nama)
print("Tempat Tgl Lahir : ", ttl)
print("Jenik Kelamin    : ", jeniskel)
print("Alamat           : ", alamat)
print("Agama            : ", agama)
if(menikah):
    print("Status           :  Menikah")
else:
    print("Status           :  Belum Menikah")
print("Pekerjaan        : ", kerja)
print("Kewarganegaraan  : ", kewarga)
print("Berlaku Hingga   : ", berlaku)
print("=============================================================")

sim = "Surat Izin Mengemudi"
tipe = "A"
noreg = ""
ttl = "minso,07-11-2002"
jeniskel = "B-laki-laki"
nama = "yunus"
alamat = """bumi
    1.025957 d, 24ʰ 37ᵐ 22.7ˢ
    bumi"""
status = "mahasiswa"
prov = "Kalimantan barat"
berlaku = "12-11-2025"
#cetak
print (sim)
print("=============================================================")

print('{:>52}'.format(tipe))
print('{:>60}'.format(noreg))


print("1. ", nama)
print("2. ", ttl)
print("3. ", jeniskel)
print("4. ", alamat)
print("5. ", status)
print("6. ", prov)

print('{:>60}'.format(berlaku))
print("=============================================================")
