---
title: ProtectionManager
second_title: Aspose.Slides dla Java – odniesienie API
description: Zarządzanie ochroną hasłem prezentacji.
type: docs
url: /pl/com.aspose.slides/protectionmanager/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Zarządzanie ochroną hasłem prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. |
| [isEncrypted()](#isEncrypted--) | Zwraca wartość wskazującą, czy ta instancja jest zaszyfrowana. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu tego pliku są publiczne. |
| [isWriteProtected()](#isWriteProtected--) | Zwraca wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Szyfruje prezentację przy użyciu podanego hasła. |
| [removeEncryption()](#removeEncryption--) | Usuwa szyfrowanie. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu podanego hasła. |
| [removeWriteProtection()](#removeWriteProtection--) | Usuwa ochronę przed zapisem dla tej prezentacji. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Określa, czy prezentacja jest zabezpieczona hasłem w celu modyfikacji. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Zwraca hasło używane do szyfrowania prezentacji. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Zwraca lub ustawia rekomendację trybu tylko do odczytu. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Zwraca lub ustawia rekomendację trybu tylko do odczytu. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli true, to właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli false, to właściwości dokumentu są publiczne, podczas gdy prezentacja jest szyfrowana. Boolean odczyt/zapis.

**Zwraca:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem. Jeśli true, to właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli false, to właściwości dokumentu są publiczne, podczas gdy prezentacja jest szyfrowana. Boolean odczyt/zapis.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Zwraca wartość wskazującą, czy ta instancja jest zaszyfrowana. Boolean tylko do odczytu.

Wartość: true, jeśli prezentacja została wczytana z zaszyfrowanego pliku lub wywołano metodę \#encrypt(String).encrypt(String); w przeciwnym razie false.

**Zwraca:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu tego pliku są publiczne. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji ładowane są tylko właściwości dokumentu bez użycia hasła. Wartość false oznacza, że cała zaszyfrowana prezentacja jest ładowana przy użyciu prawidłowego hasła, a nie tylko właściwości dokumentu. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false. Jeśli Presentation.EncryptDocumentProperties jest true, wtedy właściwość IsOnlyDocumentPropertiesLoaded jest zawsze false. Boolean tylko do odczytu.

**Zwraca:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Zwraca wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem. Boolean tylko do odczytu.

**Zwraca:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Szyfruje prezentację przy użyciu określonego hasła.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak zaszyfrować prezentację PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Hasło. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Usuwa szyfrowanie.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak ustawić ochronę przed zapisem w prezentacji.
>  
  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Usuwa ochronę przed zapisem dla tej prezentacji.

--------------------

> ```
> Ten przykładowy kod pokazuje, jak usunąć ochronę przed zapisem z prezentacji PowerPoint.
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

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest null lub puste, metoda zwraca false. |

**Zwraca:**
boolean – true, jeśli hasło jest prawidłowe; w przeciwnym razie false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Zwraca hasło używane do szyfrowania prezentacji. String tylko do odczytu.

**Zwraca:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Zwraca lub ustawia rekomendację trybu tylko do odczytu. Boolean odczyt/zapis.

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

**Zwraca:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Zwraca lub ustawia rekomendację trybu tylko do odczytu. Boolean odczyt/zapis.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |