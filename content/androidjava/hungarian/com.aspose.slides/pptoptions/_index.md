---
title: PptOptions
second_title: Aspose.Slides for Android a Java API hivatkozás alapján
description: Lehetőségeket biztosít, amelyek szabályozzák, hogy a prezentáció PPT formátumban hogyan legyen mentve.
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

Lehetőségeket biztosít, amelyek szabályozzák a prezentáció PPT formátumban történő mentését.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | A gyökérkönyvtár bejegyzésben tárolt objektumosztály GUID (CLSID) értékét képviseli. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | A gyökérkönyvtár bejegyzésben tárolt objektumosztály GUID (CLSID) értékét képviseli. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

A gyökérkönyvtár bejegyzésben tárolt objektumosztály GUID (CLSID) értékét képviseli. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-et a 'Microsoft Powerpoint.Show.8'
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

A gyökérkönyvtár bejegyzésben tárolt objektumosztály GUID (CLSID) értékét képviseli. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-et a 'Microsoft Powerpoint.Show.8'
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