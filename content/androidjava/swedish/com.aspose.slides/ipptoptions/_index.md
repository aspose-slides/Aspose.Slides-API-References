---
title: IPptOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i PPT-format.
type: docs
url: /sv/com.aspose.slides/ipptoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i PPT-format.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. Kan användas för COM-aktivering av dokumentets program. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

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
public abstract void setRootDirectoryClsid(UUID value)
```

Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. Kan användas för COM-aktivering av dokumentets program. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

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