---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Zarządzanie ochroną hasłem prezentacji.
type: docs
url: /pl/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Zarządzanie ochroną hasłem prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. |
| [isEncrypted()](#isEncrypted--) | Pobiera wartość wskazującą, czy ta instancja jest zaszyfrowana. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu tego pliku są publiczne. |
| [isWriteProtected()](#isWriteProtected--) | Pobiera wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Zwraca hasło szyfrowania. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Pobiera lub ustawia rekomendację tylko do odczytu. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Pobiera lub ustawia rekomendację tylko do odczytu. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Szyfruje prezentację podanym hasłem. |
| [removeEncryption()](#removeEncryption--) | Usuwa szyfrowanie. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ustawia ochronę przed zapisem tej prezentacji przy użyciu podanego hasła. |
| [removeWriteProtection()](#removeWriteProtection--) | Usuwa ochronę przed zapisem tej prezentacji. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Określa, czy prezentacja jest zabezpieczona hasłem przed modyfikacją. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli true, wtedy właściwości dokumentu są zaszyfrowane w pliku prezentacji. Jeśli false, wtedy właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli true, wtedy właściwości dokumentu są zaszyfrowane w pliku prezentacji. Jeśli false, wtedy właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Pobiera wartość wskazującą, czy ta instancja jest zaszyfrowana. Boolean tylko do odczytu.

Wartość: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Zwraca:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu tego pliku są publiczne. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji ładowane są tylko właściwości dokumentu bez użycia hasła. Wartość false oznacza, że cała zaszyfrowana prezentacja jest ładowana przy użyciu właściwego hasła, a nie tylko właściwości dokumentu. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false. Jeśli PresentationEx.EncryptDocumentProperties jest true, to wartość właściwości IsOnlyDocumentPropertiesLoaded jest zawsze false. Boolean tylko do odczytu.

**Zwraca:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Pobiera wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem. Boolean tylko do odczytu.

**Zwraca:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Zwraca hasło szyfrowania. String tylko do odczytu.

**Zwraca:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Pobiera lub ustawia rekomendację tylko do odczytu. Boolean odczyt/zapis.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Zwraca:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Pobiera lub ustawia rekomendację tylko do odczytu. Boolean odczyt/zapis.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Szyfruje prezentację podanym hasłem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Hasło. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Usuwa szyfrowanie.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Ustawia ochronę przed zapisem tej prezentacji przy użyciu podanego hasła.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Usuwa ochronę przed zapisem tej prezentacji.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Określa, czy prezentacja jest zabezpieczona hasłem przed modyfikacją.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia. |

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest null lub puste, metoda zwraca false. |

**Zwraca:**
boolean - True, jeśli hasło jest prawidłowe; w przeciwnym razie false.