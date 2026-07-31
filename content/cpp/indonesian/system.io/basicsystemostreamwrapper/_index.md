---
title: BasicSystemOStreamWrapper
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pembungkus seperti std::ostream yang menggunakan BasicSystemIOStreamBuf sebagai buffer internal."
type: docs
weight: 79
url: /id/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper kelas

Mewakili pembungkus seperti std::ostream yang menggunakan [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) sebagai buffer internal.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Digunakan dalam konstruktor pindah dan operator penugasan pindah untuk mengatur ulang penunjuk dan memanggil [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Membuat instance baru dari [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Konstruktor salin. Dihapus. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Konstruktor pindah. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Operator penugasan salin. Dihapus. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Operator penugasan pindah. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Pemanggilan swap *this dan **right**, jika tidak sama. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Lihat Juga

* Ruang nama [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)