---
title: Storage
second_title: Aspose.Slides for Java API Referansı
description: Geçici bir veri depolamasını temsil eder.
type: docs
url: /tr/com.aspose.slides/storage/
---
**Kalıtım:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) için geçici bir veri depolamasını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Değeri depolamaya koyar. |
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


Depolamaya değeri koyar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Değer için anahtar. |
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

**Dönüş Değeri:**
TValue - Veri koleksiyonunda mevcutsa veri değeri, null otherwise.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Depolamanın belirtilen anahtara sahip bir öğe içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Değerin anahtarı. |

**Dönüş Değeri:**
boolean - Depolama belirtilen anahtara sahip bir öğe içeriyorsa true, aksi takdirde false.