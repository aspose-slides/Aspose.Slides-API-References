---
title: WeakReference<>
second_title: Aspose.Slides for C++ API Referansı
description: Zayıf bir referansı temsil eder; bu referans bir nesneyi işaret ederken, nesnenin silinmesine izin verir.
type: docs
weight: 1522
url: /tr/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> sınıf


Zayıf bir referansı temsil eder; bu referans bir nesneyi işaret ederken, nesnenin silinmesine izin verir.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Geçerli WeakReference nesnesi tarafından referans edilen nesnenin silinip silinmediğine dair bir gösterge alır. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Geçerli WeakReference nesnesi tarafından referans edilen nesneyi (hedef) alır. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Geçerli WeakReference nesnesi tarafından referans edilen nesneyi (hedef) ayarlar. |
|  [WeakReference](./weakreference/)() | Varsayılan yapıcı. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | nullptr'tan yapıcı. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | WeakReference sınıfının yeni bir örneğini başlatır, belirtilen nesneyi referans gösterir. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | WeakReference sınıfının yeni bir örneğini başlatır, belirtilen nesneyi referans gösterir ve bir bool parametresi alır. |
## Bkz

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)