---
title: "System::TestPredicates::TypeTraits"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 963
url: /id/system.testpredicates.typetraits/
---
## Struktur

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Memeriksa apakah suatu tipe memiliki metode data(). Jika ya, mewarisi std::true_type, jika tidak mewarisi std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Spesialisasi untuk tipe BitArray yang menyediakan tipe boost yang tidak dapat diakses di sana. |
| [has_print_to_method](./has_print_to_method/) | Memeriksa overload fungsi PrintTo yang menerima tipe yang diberikan sebagai argumen pertama. Jika overload ada, mewarisi std::true_type, jika tidak mewarisi std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Memeriksa apakah tipe tertentu adalah kontainer gaya STL. Untuk melakukannya, memeriksa keberadaan tipe anggota iterator dan const_iterator. Jika keduanya ada, mewarisi std::true_type, jika tidak mewarisi std::false_type. |
| [IsEnumerable](./isenumerable/) | Memeriksa apakah tipe memiliki spesialisasi [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) sebagai tipe dasar. Jika ya, anggota value diatur ke true, jika tidak diatur ke false. |
| [LargestFPType](./largestfptype/) | Menyediakan alias untuk tipe floating point terpanjang yang tersedia. Mengabaikan tipe non-floating point. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Memeriksa bahwa **T1** bersifat aritmetika dan **T2** bertipe floating point, atau sebaliknya. Jika ya, mengatur anggota value ke true, jika tidak menjadi false. |
| [AnyOfDecimal](./anyofdecimal/) | Memeriksa bahwa setidaknya satu argumen tipe merupakan [System::Decimal](../system/decimal/). Jika ya, mengatur anggota value ke true, jika tidak menjadi false. |
| [IsArray](./isarray/) | Memeriksa apakah tipe adalah spesialisasi [System::Array](../system/array/). Jika ya, anggota value diatur ke true, jika tidak diatur ke false. |
| [IsList](./islist/) | Memeriksa apakah tipe adalah spesialisasi [System::Collections::Generic::List](../system.collections.generic/list/). Jika ya, anggota value diatur ke true, jika tidak diatur ke false. |
| [BothArrayOrList](./botharrayorlist/) | Memeriksa apakah kedua argumen tipe adalah array atau list. Jika ya, anggota value diatur ke true, jika tidak diatur ke false. |
| [BothEnumerable](./bothenumerable/) | Memeriksa apakah kedua argumen tipe adalah IEnumerable. Jika ya, anggota value diatur ke true, jika tidak diatur ke false. |