---
title: ProtectionManager
second_title: Aspose.Slides für Java API-Referenz
description: Verwaltung des Kennwortschutzes für Präsentationen.
type: docs
url: /de/com.aspose.slides/protectionmanager/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Verwaltung des Kennwortschutzes für Präsentationen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [isEncrypted()](#isEncrypted--) | Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. |
| [isWriteProtected()](#isWriteProtected--) | Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Verschlüsselt die Präsentation mit dem angegebenen Kennwort. |
| [removeEncryption()](#removeEncryption--) | Entfernt die Verschlüsselung. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Aktiviert den Schreibschutz für diese Präsentation mit dem angegebenen Kennwort. |
| [removeWriteProtection()](#removeWriteProtection--) | Entfernt den Schreibschutz für diese Präsentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ermittelt, ob eine Präsentation zum Ändern passwortgeschützt ist. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Gibt das Kennwort zurück, das für die Verschlüsselung der Präsentation verwendet wird. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Liest oder setzt die Nur-Lese-Empfehlung. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Liest oder setzt die Nur-Lese-Empfehlung. |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese-/Schreib-boolean.

**Rückgabe:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist. Nur-Lese-boolean.

Wert: true, wenn die Präsentation aus einer verschlüsselten Datei geladen wurde oder die Methode \#encrypt(String).encrypt(String) aufgerufen wurde; sonst false.

**Rückgabe:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden, ohne ein Passwort zu verwenden. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird, nicht nur die Dokumenteigenschaften. Ist die Präsentation nicht verschlüsselt, ist der Eigenschaftswert immer false. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich, ist der Eigenschaftswert immer false. Ist Presentation.EncryptDocumentProperties true, dann ist der IsOnlyDocumentPropertiesLoaded-Eigenschaftswert immer false. Nur-Lese-boolean.

**Rückgabe:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist. Nur-Lese-boolean.

**Rückgabe:**
boolean

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Verschlüsselt die Präsentation mit dem angegebenen Kennwort.

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
| encryptionPassword | java.lang.String | Das Kennwort. |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Entfernt die Verschlüsselung.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Aktiviert den Schreibschutz für diese Präsentation mit dem angegebenen Kennwort.

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
| password | java.lang.String | Das Kennwort. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Entfernt den Schreibschutz für diese Präsentation.

--------------------

> ```
> Dieser Beispielcode zeigt, wie Sie den Schreibschutz einer PowerPoint-Präsentation entfernen.
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

Ermittelt, ob eine Präsentation zum Ändern passwortgeschützt ist.

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
| password | java.lang.String | Das Kennwort zur Überprüfung. |

--------------------
1. Sie sollten die (\#isWriteProtected.isWriteProtected)-Eigenschaft prüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Kennwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**
boolean – True, wenn das Kennwort gültig ist; sonst false.

### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Gibt das Kennwort zurück, das für die Verschlüsselung der Präsentation verwendet wird. Nur-Lese-String.

**Rückgabe:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Liest oder setzt die Nur-Lese-Empfehlung. Lese-/Schreib-boolean.

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

**Rückgabe:**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Liest oder setzt die Nur-Lese-Empfehlung. Lese-/Schreib-boolean.

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