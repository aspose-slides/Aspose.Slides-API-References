---
title: PptOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im PPT-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/pptoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im PPT-Format gespeichert wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Stellt die Objektklassen-GUID (CLSID) dar, die im Wurzelverzeichnis-Eintrag gespeichert ist. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Stellt die Objektklassen-GUID (CLSID) dar, die im Wurzelverzeichnis-Eintrag gespeichert ist. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Stellt die Objektklassen-GUID (CLSID) dar, die im Wurzelverzeichnis-Eintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendungs-Dokumente verwendet werden. Der Standardwert ist ‚64818D11-4F9B-11CF-86EA-00AA00B929E8‘, der ‚Microsoft Powerpoint.Slide.8‘ entspricht.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// setze CLSID auf 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Stellt die Objektklassen-GUID (CLSID) dar, die im Wurzelverzeichnis-Eintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendungs-Dokumente verwendet werden. Der Standardwert ist ‚64818D11-4F9B-11CF-86EA-00AA00B929E8‘, der ‚Microsoft Powerpoint.Slide.8‘ entspricht.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// setze CLSID auf 'Microsoft Powerpoint.Show.8'
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