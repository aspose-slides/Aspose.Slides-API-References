---
title: Enter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen nesne üzerinde münhasır kilit alır.
type: docs
weight: 1
url: /tr/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) yöntemi

Belirtilen nesne üzerinde münhasır kilit alır.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Monitör kilidinin alınacağı nesne. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) yöntemi

Belirtilen nesne üzerinde münhasır kilit alır ve kilidin alınıp alınmadığını gösteren bir değeri atomik olarak ayarlar.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Monitor](../)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)