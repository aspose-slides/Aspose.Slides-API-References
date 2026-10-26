---
title: IPptOptions
second_title: Aspose.Slides Android számára a Java API referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a bemutató PPT formátumban.
type: docs
url: /hu/com.aspose.slides/ipptoptions/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a bemutató PPT formátumban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Az objektumosztály GUID-ját (CLSID) ábrázolja, amely a gyökérkönyvtár bejegyzésben van tárolva. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Az objektumosztály GUID-ját (CLSID) ábrázolja, amely a gyökérkönyvtár bejegyzésben van tárolva. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Az objektumosztály GUID-ját (CLSID) ábrázolja, amely a gyökérkönyvtár bejegyzésben van tárolva. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-t a 'Microsoft Powerpoint.Show.8' értékre
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Az objektumosztály GUID-ját (CLSID) ábrázolja, amely a gyökérkönyvtár bejegyzésben van tárolva. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// állítsa be a CLSID-t a 'Microsoft Powerpoint.Show.8' értékre
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