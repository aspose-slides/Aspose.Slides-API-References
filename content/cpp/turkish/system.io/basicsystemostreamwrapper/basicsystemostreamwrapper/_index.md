---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides for C++ API Referansı
description: BasicSystemOStreamWrapper sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor

Yeni bir [BasicSystemOStreamWrapper](../) örneği oluşturur.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Akışa işaretçi |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Sarma modu |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) constructor

Kopya yapıcı. Silinmiş.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) constructor

Taşıma yapıcı.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | taşınacak [Object](../../../system/object/) |

## İlgili

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../stream/)
* Sınıf [BasicSystemOStreamWrapper](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)