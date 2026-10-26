---
title: Storage
second_title: Aspose.Slides for Android için Java API Referansı
description: Geçici bir veri depolama birimini temsil eder.
type: docs
url: /tr/com.aspose.slides/storage/
---
**Kalıtım:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) için geçici bir veri depolama birimini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Storage()](#Storage--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Değeri depolamaya ekler. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Depolamadan veriyi alır. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Depolamanın belirtilen anahtara sahip bir öğe içerip içermediğini belirler. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Değeri depolamaya ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Değerin anahtarı. |
| value | TValue | Değer. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Depolamadan veriyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Değerin anahtarı. |

**Döndürür:**
TValue - Veri değeri, veri koleksiyonunda mevcutsa, aksi takdirde null.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Depolama belirtilen anahtara sahip bir öğe içeriyorsa true, aksi takdirde false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Değerin anahtarı. |

**Döndürür:**
boolean - Depolama belirtilen anahtara sahip bir öğe içeriyorsa true, aksi takdirde false.