---
title: IPptOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PPT-formaat.
type: docs
url: /nl/com.aspose.slides/ipptoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PPT-formaat.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Stelt de objectklasse-GUID (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Stelt de objectklasse-GUID (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Stelt de objectklasse-GUID (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

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

**Retourwaarde:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Stelt de objectklasse-GUID (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

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