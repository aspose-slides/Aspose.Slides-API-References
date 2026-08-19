---
title: IPptOptions
second_title: Aspose.Slides pro Java - referenční příručka API
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PPT.
type: docs
url: /cs/com.aspose.slides/ipptoptions/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PPT.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Representuje GUID objektové třídy (CLSID), který je uložen v položce kořenového adresáře. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Representuje GUID objektové třídy (CLSID), který je uložen v položce kořenového adresáře. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Representuje GUID objektové třídy (CLSID), který je uložen v položce kořenového adresáře. Lze jej použít k COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// nastavit CLSID na 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Representuje GUID objektové třídy (CLSID), který je uložen v položce kořenového adresáře. Lze jej použít k COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// nastavit CLSID na 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |