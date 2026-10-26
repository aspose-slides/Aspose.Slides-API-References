---
title: PptOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i PPT-format.
type: docs
url: /sv/com.aspose.slides/pptoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Tillhandahåller alternativ som styr hur en presentation sparas i PPT-format.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representerar objektklassens GUID (CLSID) som lagras i rotkatalogsposten. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representerar objektklassens GUID (CLSID) som lagras i rotkatalogsposten. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Representerar objektklassens GUID (CLSID) som lagras i rotkatalogsposten. Kan användas för COM-aktivering av dokumentets applikation. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// sätt CLSID till 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Representerar objektklassens GUID (CLSID) som lagras i rotkatalogsposten. Kan användas för COM-aktivering av dokumentets applikation. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// sätt CLSID till 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |