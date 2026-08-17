---
title: AudioPlayModePreset
second_title: Aspose.Slides for Java API Referansı
description: Sesin nasıl çalınacağını tanımlayan sabitler.
type: docs
url: /tr/com.aspose.slides/audioplaymodepreset/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AudioPlayModePreset extends System.Enum
```

Bir sesin nasıl çalınacağını tanımlayan sabitler.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Mixed](#Mixed) |  |
| [Auto](#Auto) | Otomatik olarak çal. |
| [OnClick](#OnClick) | Sadece simge tıklandığında çal. |
| [AllSlides](#AllSlides) | Tüm slaytlarda çal. |
| [InClickSequence](#InClickSequence) | Bir tıklama ile otomatik çal. |
### Karışık {#Mixed}
```
public static final int Mixed
```




### Otomatik {#Auto}
```
public static final int Auto
```


Otomatik olarak çal.

### Tıklandığında {#OnClick}
```
public static final int OnClick
```


Sadece simge tıklandığında çal.

### TümSlaytlar {#AllSlides}
```
public static final int AllSlides
```


Tüm slaytlarda çal. Lütfen bunun yerine ([IAudioFrame.getPlayAcrossSlides](../../com.aspose.slides/iaudioframe\#getPlayAcrossSlides)/[IAudioFrame.setPlayAcrossSlides(boolean)](../../com.aspose.slides/iaudioframe\#setPlayAcrossSlides-boolean-)) özelliğini kullanın.

--------------------

Bu öğe PowerPoint 2013'ten beri güncel değil.

### TıklamaSırası {#InClickSequence}
```
public static final int InClickSequence
```


Bir tıklama ile otomatik çal.