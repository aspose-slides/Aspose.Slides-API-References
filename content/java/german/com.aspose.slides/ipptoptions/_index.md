---
title: IPptOptions
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im PPT-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/ipptoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im PPT-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichniseintrag gespeichert ist. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichniseintrag gespeichert ist. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichniseintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendung des Dokuments verwendet werden. Der Standardwert ist '64818D11-4F9B-11CF-86EA-00AA00B929E8' und entspricht 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID auf 'Microsoft Powerpoint.Show.8' setzen
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichniseintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendung des Dokuments verwendet werden. Der Standardwert ist '64818D11-4F9B-11CF-86EA-00AA00B929E8' und entspricht 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID auf 'Microsoft Powerpoint.Show.8' setzen
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |