---
title: BasicSystemIOStreamBuf
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili buffer yang membungkus aliran mirip System::IO::Stream dan memungkinkan mereka digunakan sebagai buffer internal aliran mirip std::iostream."
type: docs
weight: 40
url: /id/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf kelas


Mewakili buffer yang membungkus aliran mirip [System::IO::Stream](../stream/) dan memungkinkan mereka digunakan sebagai buffer internal aliran mirip std::iostream-like.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Digunakan dalam konstruktor pindah dan operator penugasan pindah untuk mengatur ulang pointer dan memanggil [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Membuat instance baru dari [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Membuat instance baru dari [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Konstruktor penyalin. Dihapus. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Konstruktor pindah. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operator penugasan penyalin. Dihapus. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operator penugasan pindah. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Memanggil swap *this dan right, bila keduanya tidak sama. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Lihat Juga

* Ruang Nama [System::IO](../)
* Pustaka [Aspose.Slides](../../)