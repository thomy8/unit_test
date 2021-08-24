Pada blok it 1, test yang menguji endpoint get(‘ / ‘) untuk mendapatkan semua data siswa, ditegaskan bahwa response harus memiliki status code 200 dan return harus berupa sebuah object.

Lalu blok it 2, adalah test untuk endpoint get(‘/${id}’) untuk mendapatkan data tunggal, dan memastikan bahwa response harus memiliki status code 200 dan return harus berupa sebuah object.

Dan pada block it 3, masih test untuk endpoint get(‘/${id}’). Dengan asumsi jika data siswa tidak ada, it menegaskan bahwa response harus memiliki status code 404


Dokumentasi CHAi UNIT test bisa di dapat dari web site ini https://www.chaijs.com/
