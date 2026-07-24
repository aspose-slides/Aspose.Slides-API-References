---
title: Semaphore()
second_title: Aspose.Slides for C++ API Referansı
description: Adlandırılmamış semafor oluşturur.
type: docs
weight: 1
url: /tr/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) yapıcı


Adlandırılmamış semafor oluşturur.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| initialCount | int | Aktif girişlerin başlangıç sayısı. |
| maximumCount | int | Maksimum izin verilen giriş sayısı. |

## Semaphore::Semaphore(int, int, const String\&) yapıcı


Adlandırılmış semafor oluşturur.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| initialCount | int | Aktif girişlerin başlangıç sayısı. |
| maximumCount | int | Maksimum izin verilen giriş sayısı. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) adı. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) yapıcı


Adlandırılmış semafor oluşturur.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| initialCount | int | Aktif girişlerin başlangıç sayısı. |
| maximumCount | int | Maksimum izin verilen giriş sayısı. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) adı. |
| createdNew | **bool**\& | Semaphore oluşturulduysa **true**, aynı isimdeki mevcut semaphore yeniden kullanıldıysa **false** olarak ayarlanan değişkene referans. |

## İlgili

* Sınıf [Semaphore](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)