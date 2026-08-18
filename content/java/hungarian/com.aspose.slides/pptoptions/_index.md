---
title: PptOptions
second_title: Aspose.Slides Java API referencia
description: Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció PPT formátumban.
type: docs
url: /hu/com.aspose.slides/pptoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik egy bemutató PPT formátumban.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | A gyökérkönyvtár-bejegyzésben tárolt objektumosztály GUID-ot (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | A gyökérkönyvtár-bejegyzésben tárolt objektumosztály GUID-ot (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


A gyökérkönyvtár-bejegyzésben tárolt objektumosztály GUID-ot (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-et a 'Microsoft Powerpoint.Show.8' értékre
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
public final void setRootDirectoryClsid(UUID value)
```


A gyökérkönyvtár-bejegyzésben tárolt objektumosztály GUID-ot (CLSID) képviseli. A dokumentum alkalmazásának COM-aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-et a 'Microsoft Powerpoint.Show.8' értékre
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