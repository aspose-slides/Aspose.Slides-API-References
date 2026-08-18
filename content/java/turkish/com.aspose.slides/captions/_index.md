---
title: Captions
second_title: Aspose.Slides for Java API Referansı
description: WebVTT kapalı altyazılarını temsil eder.
type: docs
url: /tr/com.aspose.slides/captions/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

WebVTT kapalı altyazılarını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. |
| [getLabel()](#getLabel--) | Kapalı altyazıların etiketini döndürür ya da ayarlar. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Kapalı altyazıların etiketini döndürür ya da ayarlar. |
| [getBinaryData()](#getBinaryData--) | Kapalı altyazıların ikili verilerini döndürür. |
| [getDataAsString()](#getDataAsString--) | Kapalı altyazı verilerini UTF-8 kodlu string olarak döndürür. Salt-okunur String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

Kapalı altyazıların küresel olarak benzersiz tanımlayıcısını (GUID) döndürür. Salt-okunur java.util.UUID.

**Döndürür:**
java.util.UUID
### getLabel() {#getLabel--}
``` 
public final String getLabel()
```

Kapalı altyazıların etiketini döndürür ya da ayarlar. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

Kapalı altyazıların etiketini döndürür ya da ayarlar. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Kapalı altyazıların ikili verilerini döndürür. Salt-okunur  byte[] .

**Döndürür:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

Kapalı altyazı verilerini UTF-8 kodlu string olarak döndürür. Salt-okunur String.

**Döndürür:**
java.lang.String