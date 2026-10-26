---
title: AudioPlayModePreset
second_title: Aspose.Slides Java API Hivatkozás
description: A hang lejátszásának módját meghatározó állandók.
type: docs
url: /hu/com.aspose.slides/audioplaymodepreset/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AudioPlayModePreset extends System.Enum
```

A hang lejátszásának módját meghatározó állandók.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Mixed](#Mixed) |  |
| [Auto](#Auto) | Automatikusan lejátszódik. |
| [OnClick](#OnClick) | Csak akkor játszódik le, amikor az ikonra kattintanak. |
| [AllSlides](#AllSlides) | Minden dián lejátszódik. |
| [InClickSequence](#InClickSequence) | Automatikusan lejátszható kattintással. |
### Vegyes {#Mixed}
```
public static final int Mixed
```




### Automatikus {#Auto}
```
public static final int Auto
```


Automatikusan lejátszódik.

### Kattintáskor {#OnClick}
```
public static final int OnClick
```


Csak akkor játszódik le, amikor az ikonra kattintanak.

### MindenDia {#AllSlides}
```
public static final int AllSlides
```


Minden dián lejátszódik. Kérjük, használja helyette a ([IAudioFrame.getPlayAcrossSlides](../../com.aspose.slides/iaudioframe\#getPlayAcrossSlides)/[IAudioFrame.setPlayAcrossSlides(boolean)](../../com.aspose.slides/iaudioframe\#setPlayAcrossSlides-boolean-)) tulajdonságot.

--------------------

Ez az elem elavult a PowerPoint 2013 óta.

### KattintásiSor {#InClickSequence}
```
public static final int InClickSequence
```


Automatikusan lejátszható kattintással.