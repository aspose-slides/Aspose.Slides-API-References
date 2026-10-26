---
title: IPptOptions
second_title: Aspose.Slides for Java API Referencia
description: Beállításokat biztosít, amelyek szabályozzák, hogyan menthető egy prezentáció PPT formátumban.
type: docs
url: /hu/com.aspose.slides/ipptoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Beállításokat biztosít, amelyek szabályozzák, hogyan menthető egy prezentáció PPT formátumban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | A gyökérkönyvtár bejegyzésében tárolt objektumosztály GUID-ját (CLSID) képviseli. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | A gyökérkönyvtár bejegyzésében tárolt objektumosztály GUID-ját (CLSID) képviseli. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


A gyökérkönyvtár bejegyzésében tárolt objektumosztály GUID-ját (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8' amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsd be a CLSID-et 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```


A gyökérkönyvtár bejegyzésében tárolt objektumosztály GUID-ját (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8' amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsd be a CLSID-et 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |