---
title: BasicSystemIStreamWrapper
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pembungkus mirip std::istream yang menggunakan BasicSystemIOStreamBuf sebagai buffer internal."
type: docs
weight: 66
url: /id/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper kelas

Mewakili pembungkus mirip std::istream yang menggunakan [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) sebagai buffer internal.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Digunakan dalam konstruktor pindah dan operator penugasan pindah untuk mengatur ulang pointer dan memanggil [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Membuat instance baru dari [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Konstruktor penyalin. Dihapus. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Konstruktor pindah. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Operator penugasan penyalin. Dihapus. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Operator penugasan pindah. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Panggilan untuk menukar *this dan **right**, jika keduanya tidak sama. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Lihat Juga

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)