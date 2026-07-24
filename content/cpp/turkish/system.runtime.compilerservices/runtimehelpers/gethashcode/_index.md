---
title: GetHashCode()
second_title: Aspose.Slides için C++ API Referansı
description: "Arbitrary tipte hash kodunu alır. Bunu yapmak için Object::GetHashCode() çağırır."
type: docs
weight: 1
url: /tr/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) yöntemi

Arbitrary tipte hash kodunu alır. Bunu yapmak için [Object::GetHashCode()](../../../system/object/gethashcode/) çağırır.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Hash kodu alınacak tip. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | Bilgi alınacak [Object](../../../system/object/). |

### Dönüş Değeri

Hedef uygulama tarafından hesaplanan hash kod değeri.

## İlgili

* Sınıf [SmartPtr](../../../system/smartptr/)
* Sınıf [RuntimeHelpers](../)
* Ad Alanı [System::Runtime::CompilerServices](../../)
* Kütüphane [Aspose.Slides](../../../)