---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides için C++ API Referansı
description: BasicSystemIStreamWrapper'ın yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) yapıcı


Yeni bir [BasicSystemIStreamWrapper](../) örneği oluşturur.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Akışa işaretçi |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Sarma modu |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) yapıcı


Kopya yapıcı. Silinmiş.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) yapıcı


Taşıma yapıcı.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) taşınacak |

## İlgili

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)