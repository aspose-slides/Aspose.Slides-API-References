---
title: PresentationInfo
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [isEncrypted()](#isEncrypted--) | Gibt True zurück, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. |
| [isPasswordProtected()](#isPasswordProtected--) | Gibt einen Wert zurück, der anzeigt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist. |
| [isWriteProtected()](#isWriteProtected--) | Gibt einen Wert zurück, der anzeigt, ob die gebundene Präsentation schreibgeschützt ist. |
| [getLoadFormat()](#getLoadFormat--) | Gibt das Format der gebundenen Präsentation zurück. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Überprüft, ob ein Passwort für eine mit einem Öffnungspasswort geschützte Präsentation korrekt ist. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Überprüft, ob ein Änderungs-Passwort für eine schreibgeschützte Präsentation korrekt ist. |
| [readDocumentProperties()](#readDocumentProperties--) | Gibt die Dokumenteigenschaften der gebundenen Präsentation zurück. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualisiert die Eigenschaften der gebundenen Präsentation. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Schreibt die gebundene Präsentation in den Stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Schreibt die gebundene Präsentation in eine Datei. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Gibt True zurück, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False. Nur lesbar boolean.

**Rückgabe:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Gibt einen Wert zurück, der anzeigt, ob die gebundene Präsentation durch ein Öffnungspasswort geschützt ist.

--------------------

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

Gibt einen Wert zurück, der anzeigt, ob die gebundene Präsentation schreibgeschützt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Wenn die Präsentation durch ein Öffnungspasswort geschützt ist, ist der Eigenschaftswert gleich NotDefined.

**Rückgabe:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Gibt das Format der gebundenen Präsentation zurück. Nur lesbar [LoadFormat](../../com.aspose.slides/loadformat).

**Rückgabe:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Überprüft, ob ein Passwort für eine mit einem Öffnungspasswort geschützte Präsentation korrekt ist.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das zu überprüfende Passwort. |

--------------------

Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**
boolean – True, wenn die Präsentation mit einem Öffnungspasswort geschützt ist und das Passwort korrekt ist, andernfalls false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Überprüft, ob ein Änderungs-Passwort für eine schreibgeschützte Präsentation korrekt ist.

--------------------

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
| password | java.lang.String | Das zu überprüfende Passwort. |

--------------------

1. Sie sollten die Eigenschaft (#isWriteProtected.isWriteProtected) prüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**
boolean – True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. False sonst.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Gibt die Dokumenteigenschaften der gebundenen Präsentation zurück.

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualisiert die Eigenschaften der gebundenen Präsentation.

--------------------

> ```
> Dieses Beispiel zeigt, wie man die #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) Methode aufruft,
>  um die Dokumenteigenschaften zu aktualisieren, die durch den Aufruf der #readDocumentProperties.readDocumentProperties Methode zurückgegeben werden.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Schreibt die gebundene Präsentation in den Stream.

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