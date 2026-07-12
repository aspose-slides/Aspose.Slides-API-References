---
title: ProtectionManager
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Verwaltung des Passwortschutzes für Präsentationen.
type: docs
url: /de/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Verwaltung des Passwortschutzes für Präsentationen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [isEncrypted()](#isEncrypted--) | Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. |
| [isWriteProtected()](#isWriteProtected--) | Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Verschlüsselt die Präsentation mit dem angegebenen Passwort. |
| [removeEncryption()](#removeEncryption--) | Entfernt die Verschlüsselung. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort. |
| [removeWriteProtection()](#removeWriteProtection--) | Entfernt den Schreibschutz für diese Präsentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bestimmt, ob eine Präsentation zum Ändern passwortgeschützt ist. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Gibt das Passwort zurück, das für die Verschlüsselung der Präsentation verwendet wird. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Gibt die Read-Only-Empfehlung zurück oder setzt sie. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Gibt die Read-Only-Empfehlung zurück oder setzt sie. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese/Schreib-Boolean.

**Rückgabewert:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist. Nur lesbarer Boolean.

Wert: true, wenn die Präsentation aus einer verschlüsselten Datei geladen wurde oder die Methode \#encrypt(String).encrypt(String) aufgerufen wurde; andernfalls false.

**Rückgabewert:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden, ohne ein Passwort zu verwenden. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem korrekten Passwort geladen wird, nicht nur die Dokumenteigenschaften. Ist die Präsentation nicht verschlüsselt, ist der Eigenschaftswert stets false. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich, ist der Wert stets false. Ist Presentation.EncryptDocumentProperties true, ist der Wert von IsOnlyDocumentPropertiesLoaded stets false. Nur lesbarer Boolean.

**Rückgabewert:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist. Nur lesbarer Boolean.

**Rückgabewert:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Verschlüsselt die Präsentation mit dem angegebenen Passwort.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Das Passwort. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Entfernt die Verschlüsselung.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie Sie einen Schreibschutz für eine Präsentation festlegen.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das Passwort. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Entfernt den Schreibschutz für diese Präsentation.

--------------------

> ```
> Dieser Beispielcode zeigt, wie Sie den Schreibschutz von einer PowerPoint-Präsentation entfernen.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Bestimmt, ob eine Präsentation zum Ändern passwortgeschützt ist.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das Passwort zum Prüfen.

1. Sie sollten die Eigenschaft (\#isWriteProtected.isWriteProtected) prüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabewert:**
boolean - true, wenn das Passwort gültig ist; andernfalls false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Gibt das Passwort zurück, das für die Verschlüsselung der Präsentation verwendet wird. Nur lesbarer String.

**Rückgabewert:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Gibt die Read-Only-Empfehlung zurück oder setzt sie. Lese/Schreib-Boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Gibt die Read-Only-Empfehlung zurück oder setzt sie. Lese/Schreib-Boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |