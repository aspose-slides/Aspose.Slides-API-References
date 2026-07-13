---
title: OleObjectFrame
second_title: Aspose.Slides dla Androida przez odwołanie API Java
description: Reprezentuje obiekt OLE na slajdzie.
type: docs
url: /pl/com.aspose.slides/oleobjectframe/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Reprezentuje obiekt OLE na slajdzie.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Ładuje plik PPTX do obiektu prezentacji
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Uzyskuje dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Rzutuje kształt na OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Odczytuje obiekt OLE i zapisuje go na dysku
>      if (oleObjectFrame != null) {
>          // Pobiera dane osadzonego pliku
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Pobiera rozszerzenie osadzonego pliku
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Tworzy ścieżkę do zapisania wyodrębnionego pliku
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Zapisuje wyodrębnione dane
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Zwraca obiekt właściwości wypełnienia obrazu OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Zwraca lub ustawia tytuł ikony OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Zwraca lub ustawia tytuł ikony OleObject. |
| [getObjectName()](#getObjectName--) | Zwraca lub ustawia nazwę obiektu. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Zwraca lub ustawia nazwę obiektu. |
| [getObjectProgId()](#getObjectProgId--) | Zwraca ProgID obiektu. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Zwraca ProgID obiektu. |
| [getLinkFileName()](#getLinkFileName--) | Zwraca pełną ścieżkę do powiązanego pliku. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca pełną ścieżkę do powiązanego pliku. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca pełną ścieżkę do powiązanego pliku. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Zwraca względną ścieżkę do powiązanego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Zwraca nazwę pliku osadzonego obiektu OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Zwraca ścieżkę osadzonego obiektu OLE |
| [getEmbeddedData()](#getEmbeddedData--) | Zwraca lub ustawia informacje o osadzonych danych OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Ustawia informacje o osadzonych danych OLE. |
| [isObjectIcon()](#isObjectIcon--) | Określa, czy obiekt jest widoczny jako ikona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Określa, czy obiekt jest widoczny jako ikona. |
| [isObjectLink()](#isObjectLink--) | Określa, czy obiekt jest połączony z zewnętrznym plikiem. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany po otwarciu lub wydrukowaniu prezentacji. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany po otwarciu lub wydrukowaniu prezentacji. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Zwraca obiekt właściwości wypełnienia obrazu OleObject. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Zwraca lub ustawia tytuł ikony OleObject. Odczyt/zapis String.

--------------------

Gdy IsObjectIcon == false, ta wartość jest ignorowana. Ciąg może być przycięty zgodnie z rozmiarem ikony Ole.

**Zwraca:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Zwraca lub ustawia tytuł ikony OleObject. Odczyt/zapis String.

--------------------

Gdy IsObjectIcon == false, ta wartość jest ignorowana. Ciąg może być przycięty zgodnie z rozmiarem ikony Ole.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Zwraca lub ustawia nazwę obiektu. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Zwraca lub ustawia nazwę obiektu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Zwraca ProgID obiektu. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Zwraca ProgID obiektu. Tylko do odczytu String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Zwraca pełną ścieżkę do powiązanego pliku. Zostanie użyta krótka nazwa pliku. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Zwraca pełną ścieżkę do powiązanego pliku. Zostanie użyta długa nazwa pliku. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Zwraca pełną ścieżkę do powiązanego pliku. Zostanie użyta długa nazwa pliku. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Zwraca względną ścieżkę do powiązanego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg. Tylko do odczytu String.

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

W prezentacjach Ppt niektóre linki obiektów Ole mogą mieć reprezentację względną.

**Zwraca:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Zwraca nazwę pliku osadzonego obiektu OLE

**Zwraca:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Zwraca ścieżkę osadzonego obiektu OLE

**Zwraca:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Zwraca lub ustawia informacje o osadzonych danych OLE. Odczyt/zapis [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Zwraca:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Ustawia informacje o osadzonych danych OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dane osadzone [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Ta metoda zmienia właściwości obiektu, aby odzwierciedlić nowe dane i ustawia flagę IsObjectLink na false, wskazując, że obiekt OLE jest osadzony. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Określa, czy obiekt jest widoczny jako ikona. Odczyt/zapis boolean .

**Zwraca:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Określa, czy obiekt jest widoczny jako ikona. Odczyt/zapis boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Określa, czy obiekt jest połączony z zewnętrznym plikiem. Tylko do odczytu boolean .

**Zwraca:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany po otwarciu lub wydrukowaniu prezentacji. Odczyt/zapis boolean .

**Zwraca:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Określa, czy połączony osadzony obiekt jest automatycznie aktualizowany po otwarciu lub wydrukowaniu prezentacji. Odczyt/zapis boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |