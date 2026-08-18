---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
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
| [isWriteProtected()](#isWriteProtected--) | Pobiera wartość wskazującą, czy ta prezentacja jest zabezpieczona przed zapisem. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Zwraca hasło szyfrowania. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Pobiera lub ustawia rekomendację tylko do odczytu. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Pobiera lub ustawia rekomendację tylko do odczytu. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Szyfruje prezentację przy użyciu określonego hasła. |
| [removeEncryption()](#removeEncryption--) | Usuwa szyfrowanie. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła. |
| [removeWriteProtection()](#removeWriteProtection--) | Usuwa ochronę przed zapisem dla tej prezentacji. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Określa, czy prezentacja jest zabezpieczona hasłem w celu modyfikacji. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli wartość jest true, wtedy właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli wartość jest false, wtedy właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana. Zmienna typu boolean umożliwiająca odczyt i zapis.

**Zwraca:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli wartość jest true, wtedy właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli wartość jest false, wtedy właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana. Zmienna typu boolean umożliwiająca odczyt i zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Pobiera wartość wskazującą, czy ta instancja jest zaszyfrowana. Zmienna typu boolean tylko do odczytu.

Wartość: true jeśli prezentacja została wczytana z zaszyfrowanego pliku lub \#encrypt(String).encrypt(String) został wywołany; w przeciwnym razie false.

**Zwraca:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu tego pliku są publiczne. Wartość true oznacza, że tylko właściwości dokumentu zostały załadowane z zaszyfrowanego pliku prezentacji bez użycia hasła. Wartość false oznacza, że cała zaszyfrowana prezentacja została załadowana przy użyciu prawidłowego hasła, a nie tylko właściwości dokumentu. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false. Jeśli PresentationEx.EncryptDocumentProperties jest true, wartość właściwości IsOnlyDocumentPropertiesLoaded jest zawsze false. Zmienna typu boolean tylko do odczytu.

**Zwraca:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Pobiera wartość wskazującą, czy ta prezentacja jest zabezpieczona przed zapisem. Zmienna typu boolean tylko do odczytu.

**Zwraca:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Zwraca hasło szyfrowania. Zmienna typu String tylko do odczytu.

**Zwraca:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Pobiera lub ustawia rekomendację tylko do odczytu. Zmienna typu boolean umożliwiająca odczyt i zapis.

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

Pobiera lub ustawia rekomendację tylko do odczytu. Zmienna typu boolean umożliwiająca odczyt i zapis.

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

Szyfruje prezentację przy użyciu określonego hasła.

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

Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Usuwa ochronę przed zapisem dla tej prezentacji.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Określa, czy prezentacja jest zabezpieczona hasłem w celu modyfikacji.

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

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest null lub puste, ta metoda zwraca false. |

**Zwraca:**
boolean - True jeśli hasło jest prawidłowe; w przeciwnym razie false.