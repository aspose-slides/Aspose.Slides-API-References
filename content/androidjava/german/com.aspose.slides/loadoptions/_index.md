---
title: LoadOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
url: /de/com.aspose.slides/loadoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Ermöglicht das Angeben zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Erstellt neue Standard-Ladeoptionen. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Erstellt neue Ladeoptionen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Gibt die reguläre Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Gibt die reguläre Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Gibt die Symbol-Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Gibt die Symbol-Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Gibt die asiatische Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Gibt die asiatische Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getPassword()](#getPassword--) | Ruft das Passwort ab oder legt es fest. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ruft das Passwort ab oder legt es fest. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. |
| [getWarningCallback()](#getWarningCallback--) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Stellt die Optionen dar, die zum Verwalten des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, wie die Nutzung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Stellt die Optionen dar, die zum Verwalten des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, wie die Nutzung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Gibt Quellen für externe Schriften an, die in der Präsentation verwendet werden sollen. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Gibt Quellen für externe Schriften an, die in der Präsentation verwendet werden sollen. |
| [getInterruptionToken()](#getInterruptionToken--) | Das Token zur Überwachung von Unterbrechungsanfragen. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Das Token zur Überwachung von Unterbrechungsanfragen. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ruft Optionen für Tabellenkalkulationen ab. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Ruft Optionen für Tabellenkalkulationen ab. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Erstellt neue Standard-Ladeoptionen.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Erstellt neue Ladeoptionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loadFormat | int | Format einer zu ladenden Präsentation. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben [LoadFormat](../../com.aspose.slides/loadformat).

**Rückgabewert:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben [LoadFormat](../../com.aspose.slides/loadformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Gibt die reguläre Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Verwenden Sie Ladeoptionen, um die Standard-Regular- und Asian-Schriften festzulegen
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Präsentation laden
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Folienminiatur erzeugen
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF generieren
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS generieren
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Gibt die reguläre Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Gibt die Symbol-Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Gibt die Symbol-Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Gibt die asiatische Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Gibt die asiatische Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Ruft das Passwort ab oder legt es fest. Lesen/Schreiben String.

--------------------

> ```
> Das folgende Beispielcode zeigt, wie man eine passwortgeschützte PowerPoint-Präsentation öffnet.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // mit entschlüsselter Präsentation arbeiten
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Wert: Das Passwort.

**Rückgabewert:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ruft das Passwort ab oder legt es fest. Lesen/Schreiben String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // mit entschlüsselter Präsentation arbeiten
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Wert: Das Passwort.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert **true** bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Datei geladen werden und das Passwort ignoriert wird. Der Wert **false** bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und der Wert ist **true**, können die Eigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert **true** bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Datei geladen werden und das Passwort ignoriert wird. Der Wert **false** bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und der Wert ist **true**, können die Eigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Rückgabewert:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Stellt die Optionen dar, die zum Verwalten des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, wie die Nutzung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. Diese Optionen sollen das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung bereitstellen.

--------------------

Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio-, Video- oder Präsentationsdatei sein.

**Rückgabewert:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Stellt die Optionen dar, die zum Verwalten des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, wie die Nutzung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. Diese Optionen sollen das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung bereitstellen.

--------------------

Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio-, Video- oder Präsentationsdatei sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Gibt Quellen für externe Schriften an, die in der Präsentation verwendet werden sollen. Diese Schriften stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabewert:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Gibt Quellen für externe Schriften an, die in der Präsentation verwendet werden sollen. Diese Schriften stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.

--------------------

> ```
> Das folgende Beispiel zeigt, wie benutzerdefinierte Schriftarten für eine PowerPoint-Präsentation festgelegt werden.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // mit der Präsentation arbeiten
>  // CustomFont1, CustomFont2 sowie Schriftarten aus den Ordnern assets\fonts & global\fonts und deren Unterordnern stehen der Präsentation zur Verfügung
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Das Token zur Überwachung von Unterbrechungsanfragen.

--------------------

Dieses Token verwaltet die gesamte [IPresentation](../../com.aspose.slides/ipresentation)-Instanzlebensdauer. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-Methode des [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) unterbrochen.

**Rückgabewert:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Das Token zur Überwachung von Unterbrechungsanfragen.

--------------------

Dieses Token verwaltet die gesamte [IPresentation](../../com.aspose.slides/ipresentation)-Instanzlebensdauer. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-Methode des [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) unterbrochen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. Lesen/Schreiben [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Rückgabewert:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. Lesen/Schreiben [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Ruft Optionen für Tabellenkalkulationen ab. Zum Beispiel beeinflussen diese Optionen die Berechnung von Formeln für Diagramme.

**Rückgabewert:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Ruft Optionen für Tabellenkalkulationen ab. Zum Beispiel beeinflussen diese Optionen die Berechnung von Formeln für Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> Example:
>   
>  // Verwenden Sie Ladeoptionen, um die Standard-Textkultur festzulegen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Neues Rechteck-Shape mit Text hinzufügen
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Prüfen Sie die Sprache der ersten Portion
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> Example:
>   
>  // Verwenden Sie Ladeoptionen, um die Standard-Textkultur festzulegen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Neues Rechteck-Shape mit Text hinzufügen
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Prüfen Sie die Sprache der ersten Portion
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

Die Typen der eingebetteten Binärobjekte:

Lesen/Schreiben boolean .

--------------------

> ```
> Das folgende Beispiel zeigt, wie die Präsentation ohne eingebettete Binärobjekte geladen wird.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Standard ist **false**.

**Rückgabewert:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

Die Typen der eingebetteten Binärobjekte:

Lesen/Schreiben boolean .

--------------------

> ```
> Das folgende Beispiel zeigt, wie die Präsentation ohne eingebettete Binärobjekte geladen wird.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |