---
title: ISlideShowTransition class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islideshowtransition/
---
## ISlideShowTransition kelas

Mewakili transisi pertunjukan slide.

Tipe ISlideShowTransition menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`sound`](/slides/python-net/id/aspose.slides/islideshowtransition/sound/) | Mengembalikan atau mengatur data audio yang tertanam.<br/>            Read-write [`IAudio`](/slides/python-net/id/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/id/aspose.slides/islideshowtransition/sound_mode/) | Mengatur atau mengembalikan mode suara untuk transisi slide.<br/>            Read-write [`TransitionSoundMode`](/slides/python-net/id/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/id/aspose.slides/islideshowtransition/sound_loop/) | Atribut ini menentukan apakah suara akan berulang hingga peristiwa suara berikutnya terjadi dalam<br/>            pertunjukan slide.<br/>            Read-write **bool**. |
| [`advance_on_click`](/slides/python-net/id/aspose.slides/islideshowtransition/advance_on_click/) | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak<br/>            ditentukan maka nilai true diasumsikan.<br/>            Read-write **bool**. |
| [`advance_after`](/slides/python-net/id/aspose.slides/islideshowtransition/advance_after/) | Atribut ini menentukan apakah pertunjukan slide akan pindah ke slide berikutnya setelah waktu tertentu.<br/>            Read/write **bool**. |
| [`advance_after_time`](/slides/python-net/id/aspose.slides/islideshowtransition/advance_after_time/) | Menentukan waktu, dalam milidetik, setelah mana transisi harus dimulai. Pengaturan ini<br/>            dapat digunakan bersama atribut advClick. Jika atribut ini tidak ditentukan<br/>            maka diasumsikan tidak ada kemajuan otomatis.<br/>            Read-write **int**. |
| [`speed`](/slides/python-net/id/aspose.slides/islideshowtransition/speed/) | Menentukan kecepatan transisi yang akan digunakan saat beralih dari slide saat ini<br/>            ke slide berikutnya.<br/>            Read-write [`TransitionSpeed`](/slides/python-net/id/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/id/aspose.slides/islideshowtransition/value/) | Nilai transisi pertunjukan slide.<br/>            Read-only [`ITransitionValueBase`](/slides/python-net/id/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/id/aspose.slides/islideshowtransition/type/) | Jenis transisi.<br/>            Read-write [`TransitionType`](/slides/python-net/id/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/id/aspose.slides/islideshowtransition/sound_is_built_in/) | Menentukan apakah suara ini merupakan suara bawaan atau tidak. Jika atribut ini diatur ke true maka<br/>            aplikasi pembuat akan diberitahu untuk memeriksa atribut name yang ditentukan untuk suara ini<br/>            dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan.<br/>            Read-write **bool**. |
| [`sound_name`](/slides/python-net/id/aspose.slides/islideshowtransition/sound_name/) | Menentukan nama yang dapat dibaca manusia untuk suara transisi. Properti [`ISlideShowTransition.sound`](/slides/python-net/id/aspose.slides/islideshowtransition/sound) harus diatur untuk mendapatkan atau mengatur nama suara.<br/>            Read-write **str**. |
| [`duration`](/slides/python-net/id/aspose.slides/islideshowtransition/duration/) | Mengambil atau mengatur durasi efek transisi slide dalam milidetik.<br/>            Read/write **int**. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)