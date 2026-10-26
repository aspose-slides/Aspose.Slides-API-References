---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides için C++ API Referansı
description: BasicSystemIOStreamBuf'ın yeni bir örneğini oluşturur.
type: docs
weight: 14
url: /tr/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() yapıcı

Yeni bir [BasicSystemIOStreamBuf](../) örneği oluşturur.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) yapıcı

Yeni bir [BasicSystemIOStreamBuf](../) örneği oluşturur.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Akışa akıllı işaretçi |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Kapsama modu |
| locale | const std::locale\& | [Stream](../../stream/)'nin yerel ayarı |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) yapıcı

Kopya yapıcı. Silinmiş.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) yapıcı

Taşıma yapıcı.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) taşınacak |

## İlgili

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [BasicSystemIOStreamBuf](../)
* Sınıf [Stream](../../stream/)
* İsim Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)