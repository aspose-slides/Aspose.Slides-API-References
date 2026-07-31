---
title: SlideShowTransition
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili transisi pertunjukan slide.
type: docs
weight: 404
url: /id/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition kelas


Mewakili transisi pertunjukan slide.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Menentukan apakah dua instance [SlideShowTransition](./) adalah sama. Baca/tulis **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik [Object.Equals](../../system/object/equals/) C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Atribut ini menentukan apakah pertunjukan slide akan beralih ke slide berikutnya setelah waktu tertentu. Baca **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Menentukan waktu, dalam milidetik, setelah transisi harus dimulai. Pengaturan ini dapat digunakan bersamaan dengan atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada auto-maju. Baca **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Baca **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Mendapatkan durasi efek transisi slide dalam milidetik. Baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Mengembalikan data audio tertanam. Baca [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Menentukan apakah suara ini merupakan suara bawaan atau tidak. Jika atribut ini diset ke true maka aplikasi pembuat akan diberi tahu untuk memeriksa atribut name yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Membaca **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. Baca **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Mengatur atau mengembalikan mode suara untuk transisi slide. Baca [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Menentukan nama yang dapat dibaca manusia untuk suara transisi. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Membaca [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. Baca [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Jenis transisi. Baca [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) nilai transisi yang ditampilkan. Hanya-baca [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. Memungkinkan pengkloningan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Atribut ini menentukan apakah pertunjukan slide akan beralih ke slide berikutnya setelah waktu tertentu. Tulis **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Menentukan waktu, dalam milidetik, setelah transisi harus dimulai. Pengaturan ini dapat digunakan bersama atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada auto-maju. Tulis **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Tulis **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Mengatur durasi efek transisi slide dalam milidetik. Tulis **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Mengatur data audio tertanam. Tulis [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Menentukan apakah suara ini merupakan suara bawaan atau tidak. Jika atribut ini diset ke true maka aplikasi pembuat akan diberi tahu untuk memeriksa atribut name yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Menulis **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. Tulis **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Mengatur atau mengembalikan mode suara untuk transisi slide. Tulis [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Menentukan nama yang dapat dibaca manusia untuk suara transisi. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Menulis [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. Tulis [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Jenis transisi. Tulis [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode [Object.ToString()](../../system/object/tostring/) C#. Memungkinkan mengkonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk [System.Object](../../system/object/) typeof C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [DomObject](../../aspose.slides/domobject/)
* Kelas [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Ruang Nama [Aspose::Slides::SlideShow](../)
* Perpustakaan [Aspose.Slides](../../)