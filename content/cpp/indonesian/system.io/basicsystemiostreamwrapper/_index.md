---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides untuk Referensi API C++
description: "Mewakili pembungkus mirip std::iostream yang menggunakan BasicSystemIOStreamBuf sebagai buffer internal."
type: docs
weight: 53
url: /id/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper kelas

Mewakili pembungkus mirip std::iostream yang menggunakan [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) sebagai buffer internal.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metode

| Method | Deskripsi |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Digunakan dalam konstruktor pindah dan operator penugasan pindah untuk menyetel ulang pointer dan memanggil [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Membuat instance baru dari [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Konstruktor penyalinan. Dihapus. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Konstruktor pindah. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Operator penugasan penyalinan. Dihapus. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Operator penugasan pindah. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Memanggil swap *this dan **right**, jika keduanya tidak sama. |

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