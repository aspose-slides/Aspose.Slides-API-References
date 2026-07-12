---
title: ILoadOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
url: /de/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Ermöglicht das Festlegen zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Gibt die reguläre Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Gibt die reguläre Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Gibt die Symbolschriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Gibt die Symbolschriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Gibt die asiatische Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Gibt die asiatische Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. |
| [getPassword()](#getPassword--) | Liest oder setzt das Passwort. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. |
| [getWarningCallback()](#getWarningCallback--) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird, oder legt es fest. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird, oder legt es fest. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu verwalten, z. B. die Verwendung temporärer Dateien oder die maximalen BLOB-Bytes im Speicher. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu verwalten, z. B. die Verwendung temporärer Dateien oder die maximalen BLOB-Bytes im Speicher. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Gibt die Quellen für externe Schriften an, die von der Präsentation verwendet werden. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Gibt die Quellen für externe Schriften an, die von der Präsentation verwendet werden. |
| [getInterruptionToken()](#getInterruptionToken--) | Das Token zur Überwachung von Unterbrechungsanfragen. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Das Token zur Überwachung von Unterbrechungsanfragen. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet, oder legt sie fest. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten festzulegen. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten festzulegen. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löscht. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löscht. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben [LoadFormat](../../com.aspose.slides/loadformat).

**Rückgabe:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben [LoadFormat](../../com.aspose.slides/loadformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Gibt die reguläre Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Gibt die reguläre Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Gibt die Symbolschriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Gibt die Symbolschriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Gibt die asiatische Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Gibt die asiatische Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht nicht gefunden wird, oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Liest oder setzt das Passwort. Lesen/Schreiben String.

Wert: Das Passwort.

**Rückgabe:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Liest oder setzt das Passwort. Lesen/Schreiben String.

Wert: Das Passwort.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Rückgabe:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu verwalten, z. B. die Verwendung temporärer Dateien oder die maximalen BLOB-Bytes im Speicher. Diese Optionen dienen dazu, das optimale Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festzulegen.

--------------------

Ein Binary Large Object (BLOB) ist ein Binärdaten, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, ein Video oder die Präsentation selbst sein.

**Rückgabe:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu verwalten, z. b. die Verwendung temporärer Dateien oder die maximalen BLOB-Bytes im Speicher. Diese Optionen dienen dazu, das optimale Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festzulegen.

--------------------

Ein Binary Large Object (BLOB) ist ein Binärdaten, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, ein Video oder die Präsentation selbst sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Gibt die Quellen für externe Schriften an, die von der Präsentation verwendet werden. Diese Schriften stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.

**Rückgabe:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Gibt die Quellen für externe Schriften an, die von der Präsentation verwendet werden. Diese Schriften stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Das Token zur Überwachung von Unterbrechungsanfragen.

--------------------

Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../com.aspose.slides/ipresentation)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-Methode der [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) unterbrochen.

**Rückgabe:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Das Token zur Überwachung von Unterbrechungsanfragen.

--------------------

Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../com.aspose.slides/ipresentation)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-Methode der [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) unterbrochen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet. Lesen/Schreiben [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Rückgabe:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Gibt die Callback-Schnittstelle zurück, die das Laden externer Ressourcen verwaltet. Lesen/Schreiben [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten festzulegen.

**Rückgabe:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten festzulegen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> Example:
>   
>  // Verwenden Sie Ladeoptionen, um die Standardsprache des Textes festzulegen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Neues Rechteck-Shape mit Text hinzufügen
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Überprüfen Sie die Sprache des ersten Abschnitts
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lesen/Schreiben String.

--------------------

> ```
> Example:
>   
>  // Verwenden Sie Ladeoptionen, um die Standardsprache des Textes festzulegen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Neues Rechteck-Shape mit Text hinzufügen
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Überprüfen Sie die Sprache des ersten Abschnitts
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löschen wird.

Die Arten der eingebetteten Binärobjekte:

 *  
 *  
 *  

Lesen/Schreiben boolean.

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

**Rückgabe:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löschen wird.

Die Arten der eingebetteten Binärobjekte:

 *  
 *  
 *  

Lesen/Schreiben boolean.

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