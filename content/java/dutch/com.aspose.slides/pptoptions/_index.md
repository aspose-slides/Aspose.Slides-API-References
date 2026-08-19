---
title: PptOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PPT-formaat.
type: docs
url: /nl/com.aspose.slides/pptoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PPT-formaat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representeert de objectklasse-GUID (CLSID) die is opgeslagen in de rootdirectory-entry. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representeert de objectklasse-GUID (CLSID) die is opgeslagen in de rootdirectory-entry. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Representeert de objectklasse-GUID (CLSID) die is opgeslagen in de rootdirectory-entry. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// stel CLSID in op 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Representeert de objectklasse-GUID (CLSID) die is opgeslagen in de rootdirectory-entry. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// stel CLSID in op 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |