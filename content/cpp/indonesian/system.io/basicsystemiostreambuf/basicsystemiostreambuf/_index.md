---
title: BasicSystemIOStreamBuf()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /id/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() konstruktor

Membuat instance baru dari [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) konstruktor

Membuat instance baru dari [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Smart pointer ke stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modus pembungkus |
| locale | const std::locale\& | [Stream](../../stream/) locale |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) konstruktor

Konstruktor penyalinan. Dihapus.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) konstruktor

Konstruktor pemindahan.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) yang akan dipindahkan |

## Lihat Juga

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [BasicSystemIOStreamBuf](../)
* Kelas [Stream](../../stream/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)