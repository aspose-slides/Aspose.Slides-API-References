---
title: PresentationInfo
second_title: Aspose.Slides für Java API Referenz
description: Informationen zur Präsentationsdatei
type: docs
url: /de/com.aspose.slides/presentationinfo/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informationen zur Präsentationsdatei
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Liefert True, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. |
| [isPasswordProtected()](#isPasswordProtected--) | Liefert einen Wert, der angibt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist. |
| [isWriteProtected()](#isWriteProtected--) | Liefert einen Wert, der angibt, ob die gebundene Präsentation schreibgeschützt ist. |
| [getLoadFormat()](#getLoadFormat--) | Liefert das Format der gebundenen Präsentation. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Prüft, ob ein Passwort für eine mit Öffnungspasswort geschützte Präsentation korrekt ist. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Prüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist. |
| [readDocumentProperties()](#readDocumentProperties--) | Liefert Dokumenteigenschaften der gebundenen Präsentation. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualisiert Eigenschaften der gebundenen Präsentation. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Schreibt die gebundene Präsentation in einen Stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Schreibt die gebundene Präsentation in eine Datei. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Liefert True, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. Nur lesbarer boolean.

**Rückgabe:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Liefert einen Wert, der angibt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Rückgabe:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Liefert einen Wert, der angibt, ob die gebundene Präsentation schreibgeschützt ist.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

---

Wenn die Präsentation durch ein Öffnungspasswort geschützt ist, hat der Eigenschaftswert NotDefined.

**Rückgabe:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Liefert das Format der gebundenen Präsentation. Nur lesbar [LoadFormat](../../com.aspose.slides/loadformat).

**Rückgabe:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Prüft, ob ein Passwort für eine mit Öffnungspasswort geschützte Präsentation korrekt ist.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das zu prüfende Passwort. |

Wenn das Passwort null oder leer ist, liefert diese Methode false.

**Rückgabe:**
boolean - True, wenn die Präsentation mit Öffnungspasswort geschützt ist und das Passwort korrekt ist, andernfalls false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Prüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das zu prüfende Passwort. |

1. Sie sollten die (\#isWriteProtected.isWriteProtected) Eigenschaft überprüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, liefert diese Methode false.

**Rückgabe:**
boolean - True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. Andernfalls false.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Liefert Dokumenteigenschaften der gebundenen Präsentation.

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualisiert Eigenschaften der gebundenen Präsentation.

---

> ```
> Dieses Beispiel zeigt, wie die #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDDocumentProperties) Methode aufgerufen wird, um
>  die Dokumenteigenschaften zu aktualisieren, die durch den Aufruf der #readDocumentProperties.readDocumentProperties Methode zurückgegeben werden.
>  
>  IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Schreibt die gebundene Präsentation in einen Stream.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream muss suchbar und schreibbar sein. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Schreibt die gebundene Präsentation in eine Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Präsentationsdatei. |