# homework_liebrapermana

Sofyan Said Atsaurry 

[Home Work] Recruitment PT Liebra Permana : ABAP Developer
1. Buatlah Program Z, dengan kriteria :
   a. 1 buah input field type string length 255
   b. program harus membalik kata yang diinput sebagai berikut,
      contoh-input : PT Liebra Permana
      contoh-output : Permana
		      Permana Liebra 
		      Permana Liebra PT


      contoh-input : PT Liebra Permana Pluit
      contoh-output : Pluit
		      Pluit Permana
		      Pluit Permana Liebra
		      Pluit Permana Liebra PT

    c. Output ditampilkan dalam POP-UP
    d. Program tidak di-hardcode [index-number, string output, etc]


   Kirimkan hanya Script program nya saja.

2. Buatlah Table Z_BOM, dengan kolom sebagai berikut :
   MATNR --> string, length-5
   IDNRK --> string, length-5


   Buatlah program Z, dengan kriteria :
   a. Program menginisasi dengan meng-insert data ke dalam table Z_BOM tersebut dengan value berikut : 
      MATNR  | IDNRK
      MAT-3  | MAT-2
	MAT-2	 | MAT-4
	MAT-4	 | MAT-8
	MAT-7	 | MAT-9
	MAT-9  | MAT-5
	MAT-5	 | MAT-1
	  
	b. Program memproses data di Z_BOM tersebut dengan menyusun hierarki
	   MATNR adalah Parent
	   IDNRK adalah Child
	   
	   Sehingga,
	   MAT-3 adalah Parent dari MAT-2, MAT-2 adalah Parent dari MAT-4, MAT-4 adalah Parent MAT-8
	   MAT-7 adalah Parent dari MAT-9, MAT-9 adalah Parent dari MAT-5, MAT-5 adalah Parent dari MAT-1
	   
	   Program menyusun Output sebgai berikut : 
	   MAT-3, MAT-2, MAT-4, MAT-8
	   MAT-7, MAT-9, MAT05, MAT-1
	   
	 c. Output ditampilkan di report grid dengan column name
	    Level#1 | Level#2 | Level#3 | Level#4
		MAT-3   | MAT-2   | MAT-4   | MAT-8
		MAT-7   | MAT-9   | MAT-5   | MAT-1
