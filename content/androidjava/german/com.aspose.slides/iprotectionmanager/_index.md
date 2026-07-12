---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Verwaltung des Präsentations-Passwortschutzes.
type: docs
url: /de/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Verwaltung des Präsentations-Passwortschutzes.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. |
| [isEncrypted()](#isEncrypted--) | Gibt einen Wert zurück, der anzeigt, ob diese Instanz verschlüsselt ist. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. |
| [isWriteProtected()](#isWriteProtected--) | Gibt einen Wert zurück, der anzeigt, ob diese Präsentation schreibgeschützt ist. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Gibt das Verschlüsselungspasswort zurück. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Liest oder setzt die Empfehlung für schreibgeschützt. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Liest oder setzt die Empfehlung für schreibgeschützt. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Verschlüsselt die Präsentation mit dem angegebenen Passwort. |
| [removeEncryption()](#removeEncryption--) | Entfernt die Verschlüsselung. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort. |
| [removeWriteProtection()](#removeWriteProtection--) | Entfernt den Schreibschutz für diese Präsentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bestimmt, ob eine Präsentation zum Ändern passwortgeschützt ist. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese-/Schreib-Boolean.

**Rückgabe:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist. Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt. Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Gibt einen Wert zurück, der anzeigt, ob diese Instanz verschlüsselt ist. Nur-Lese-Boolean.

Wert: true, wenn die Präsentation aus einer verschlüsselten Datei geladen wurde oder die Methode \#encrypt(String).encrypt(String) aufgerufen wurde; sonst false.

**Rückgabe:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind. Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei ohne Passwort geladen werden. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird, nicht nur die Dokumenteigenschaften. Wenn die Präsentation nicht verschlüsselt ist, ist der Eigenschaftswert stets false. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind, ist der Eigenschaftswert stets false. Wenn PresentationEx.EncryptDocumentProperties true ist, ist der Wert von IsOnlyDocumentPropertiesLoaded stets false. Nur-Lese-Boolean.

**Rückgabe:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Gibt einen Wert zurück, der anzeigt, ob diese Präsentation schreibgeschützt ist. Nur-Lese-Boolean.

**Rückgabe:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Gibt das Verschlüsselungspasswort zurück. Nur-Lese-String.

**Rückgabe:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Liest oder setzt die Empfehlung für schreibgeschützt. Lese-/Schreib-Boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Rückgabe:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Liest oder setzt die Empfehlung für schreibgeschützt. Lese-/Schreib-Boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Verschlüsselt die Präsentation mit dem angegebenen Passwort.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Das Passwort. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Entfernt die Verschlüsselung.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | java.lang.String | Das Passwort. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Entfernt den Schreibschutz für diese Präsentation.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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
| password | java.lang.String | Das Passwort zum Überprüfen.

--------------------

1. Sie sollten die (\#isWriteProtected.isWriteProtected) Eigenschaft überprüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. |

**Rückgabe:**  
boolean – True, wenn das Passwort gültig ist; sonst false.