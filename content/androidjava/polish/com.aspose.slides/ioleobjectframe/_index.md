---
title: IOleObjectFrame
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Reprezentuje obiekt OLE na slajdzie.
type: docs
url: /pl/com.aspose.slides/ioleobjectframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Reprezentuje obiekt OLE na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Zwraca obiekt właściwości wypełnienia obrazu OleObject. |
| [getObjectName()](#getObjectName--) | Zwraca lub ustawia nazwę obiektu. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Zwraca lub ustawia nazwę obiektu. |
| [getEmbeddedData()](#getEmbeddedData--) | Pobiera informacje o osadzonych danych OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Ustawia informacje o osadzonych danych OLE. |
| [getObjectProgId()](#getObjectProgId--) | Zwraca ProgID obiektu. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Zwraca ProgID obiektu. |
| [getLinkFileName()](#getLinkFileName--) | Zwraca pełną ścieżkę do połączonego pliku. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca pełną ścieżkę do połączonego pliku. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca pełną ścieżkę do połączonego pliku. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Zwraca względną ścieżkę do połączonego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Zwraca nazwę pliku osadzonego obiektu OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Zwraca ścieżkę osadzonego obiektu OLE |
| [isObjectIcon()](#isObjectIcon--) | Określa, czy obiekt jest widoczny jako ikona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Określa, czy obiekt jest widoczny jako ikona. |
| [isObjectLink()](#isObjectLink--) | Określa, czy obiekt jest połączony z plikiem zewnętrznym. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany, gdy prezentacja jest otwierana lub drukowana. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany, gdy prezentacja jest otwierana lub drukowana. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Zwraca lub ustawia tytuł ikony OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Zwraca lub ustawia tytuł ikony OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Zwraca obiekt właściwości wypełnienia obrazu OleObject. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Zwraca lub ustawia nazwę obiektu. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Zwraca lub ustawia nazwę obiektu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Pobiera informacje o osadzonych danych OLE. Tylko do odczytu [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Zwraca:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Ustawia informacje o osadzonych danych OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Osadzone dane [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Ta metoda zmienia właściwości obiektu, aby odzwierciedlić nowe dane i ustawia flagę IsObjectLink na false, wskazując, że obiekt OLE jest osadzony.
|

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Zwraca ProgID obiektu. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Zwraca ProgID obiektu. Tylko do odczytu String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Zwraca pełną ścieżkę do połączonego pliku. Używana będzie krótka nazwa pliku. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Zwraca pełną ścieżkę do połączonego pliku. Używana będzie długa nazwa pliku. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Zwraca pełną ścieżkę do połączonego pliku. Używana będzie długa nazwa pliku. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Zwraca względną ścieżkę do połączonego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg. Tylko do odczytu String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

W prezentacjach PPT niektóre linki do obiektów Ole mogą mieć reprezentację względną.

**Zwraca:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Zwraca nazwę pliku osadzonego obiektu OLE

**Zwraca:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Zwraca ścieżkę osadzonego obiektu OLE

**Zwraca:**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Określa, czy obiekt jest widoczny jako ikona. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Określa, czy obiekt jest widoczny jako ikona. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Określa, czy obiekt jest połączony z plikiem zewnętrznym. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany, gdy prezentacja jest otwierana lub drukowana. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany, gdy prezentacja jest otwierana lub drukowana. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Zwraca lub ustawia tytuł ikony OleObject. Odczyt/zapis String.

--------------------

Gdy IsObjectIcon == false, ta wartość jest ignorowana. Ciąg może być przycięty w zależności od rozmiaru ikony OLE.

**Zwraca:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Zwraca lub ustawia tytuł ikony OleObject. Odczyt/zapis String.

--------------------

Gdy IsObjectIcon == false, ta wartość jest ignorowana. Ciąg może być przycięty w zależności od rozmiaru ikony OLE.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |