---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API Referansı
description: ExceptionWrapper sınıfının hiçbir istisna temsil etmeyen null örneğini oluşturur.
type: docs
weight: 14
url: /tr/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) yapıcı


[ExceptionWrapper](../) sınıfının hiçbir istisna temsil etmeyen null örneğini oluşturur.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) yapıcı


[ExceptionWrapper](../) sınıfının verilen işaretçiyi içeren bir örneğini oluşturur.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Exception sınıfının örneğine akıllı işaretçi. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) yapıcı


Kopya yapıcı.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Kopyalanması gereken sarmalayıcı sınıfının diğer örneği. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) yapıcı


Taşıma yapıcı.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Taşınması gereken sarmalayıcı sınıfının diğer örneği. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) yapıcı


Parametreleri Exception sınıfı yapıcılarına yönlendiren ve yeni Exception sınıfı örneğini tutan akıllı işaretçi oluşturan yapıcı.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Bakınız

* Typedef [ExceptionPtr](../../exceptionptr/)
* Sınıf [ExceptionWrapper](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)