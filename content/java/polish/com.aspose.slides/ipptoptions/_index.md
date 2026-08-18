---
title: IPptOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie PPT.
type: docs
url: /pl/com.aspose.slides/ipptoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie PPT.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Reprezentuje GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ustaw CLSID na 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

Reprezentuje GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ustaw CLSID na 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |