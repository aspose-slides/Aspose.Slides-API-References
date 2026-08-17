---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Informationen zur Präsentationsdatei
type: docs
url: /de/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informationen zur Präsentationsdatei
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Gibt True zurück, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. |
| [isPasswordProtected()](#isPasswordProtected--) | Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist. |
| [isWriteProtected()](#isWriteProtected--) | Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation schreibgeschützt ist. |
| [getLoadFormat()](#getLoadFormat--) | Gibt das Format der gebundenen Präsentation zurück. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Prüft, ob ein Passwort für eine mit einem Öffnungspasswort geschützte Präsentation korrekt ist. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Prüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist. |
| [readDocumentProperties()](#readDocumentProperties--) | Gibt die Dokumenteigenschaften der gebundenen Präsentation zurück. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualisiert die Eigenschaften der gebundenen Präsentation. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Schreibt die gebundene Präsentation in einen Stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Schreibt die gebundene Präsentation in eine Datei. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Gibt True zurück, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. Nur lesbar boolean.

**Rückgabe:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Rückgabe:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation schreibgeschützt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Wenn die Präsentation durch ein Öffnungspasswort geschützt ist, hat der Eigenschaftswert NotDefined. Siehe die Enumeration [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Gibt das Format der gebundenen Präsentation zurück. Nur lesbar [LoadFormat](../../com.aspose.slides/loadformat).

**Rückgabe:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Prüft, ob ein Passwort für eine mit einem Öffnungspasswort geschützte Präsentation korrekt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das zu prüfende Passwort. |

--------------------

Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**
boolean - True, wenn die Präsentation mit einem Öffnungspasswort geschützt ist und das Passwort korrekt ist, andernfalls false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Prüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das zu prüfende Passwort. |

1. Sie sollten die (\#isWriteProtected.isWriteProtected) Eigenschaft prüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**
boolean - True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. Andernfalls False.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Gibt die Dokumenteigenschaften der gebundenen Präsentation zurück.

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Dokumenteigenschaften [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualisiert die Eigenschaften der gebundenen Präsentation.

--------------------

> ```
> Dieses Beispiel zeigt, wie die Methode #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) aufgerufen wird, um
>  die Dokumenteigenschaften zu aktualisieren, die durch den Aufruf der Methode #readDocumentProperties.readDocumentProperties zurückgegeben werden.
>  
>  IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Dokumenteigenschaften [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Schreibt die gebundene Präsentation in einen Stream.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream muss suchbar und schreibbar sein. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Schreibt die gebundene Präsentation in eine Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Präsentationsdatei. |