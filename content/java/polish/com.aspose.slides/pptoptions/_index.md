---
title: PptOptions
second_title: Aspose.Slides dla Java – odniesienie do API
description: Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie PPT.
type: docs
url: /pl/com.aspose.slides/pptoptions/
---
**Dziedziczenie:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable  
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Zapewnia opcje, które kontrolują sposób zapisywania prezentacji w formacie PPT.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w głównym wpisie katalogu. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w głównym wpisie katalogu. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w głównym wpisie katalogu. Może być użyty do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8' odpowiadająca 'Microsoft Powerpoint.Slide.8'.

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
public final void setRootDirectoryClsid(UUID value)
```

Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w głównym wpisie katalogu. Może być użyty do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8' odpowiadająca 'Microsoft Powerpoint.Slide.8'.

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