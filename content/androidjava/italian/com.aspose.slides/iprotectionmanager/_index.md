---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Gestione della protezione con password della presentazione.
type: docs
url: /it/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Gestione della protezione con password della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Questa proprietà ha senso, se la presentazione è protetta da password. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Questa proprietà ha senso, se la presentazione è protetta da password. |
| [isEncrypted()](#isEncrypted--) | Restituisce un valore che indica se questa istanza è crittografata. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. |
| [isWriteProtected()](#isWriteProtected--) | Restituisce un valore che indica se questa presentazione è protetta dalla scrittura. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Restituisce la password di crittografia. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Ottiene o imposta la raccomandazione di sola lettura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Ottiene o imposta la raccomandazione di sola lettura. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Cifra la presentazione con la password specificata. |
| [removeEncryption()](#removeEncryption--) | Rimuove la crittografia. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Imposta la protezione dalla scrittura per questa presentazione con la password specificata. |
| [removeWriteProtection()](#removeWriteProtection--) | Rimuove la protezione dalla scrittura per questa presentazione. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina se una presentazione è protetta da password per la modifica. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Questa proprietà ha senso, se la presentazione è protetta da password. Se vero, le proprietà del documento sono crittografate nel file della presentazione. Se falso, le proprietà del documento sono pubbliche mentre la presentazione è crittografata. Booleano lettura/scrittura.

**Restituisce:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Questa proprietà ha senso, se la presentazione è protetta da password. Se vero, le proprietà del documento sono crittografate nel file della presentazione. Se falso, le proprietà del documento sono pubbliche mentre la presentazione è crittografata. Booleano lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Restituisce un valore che indica se questa istanza è crittografata. Booleano di sola lettura.

Valore: true se la presentazione è stata caricata da un file crittografato o è stato chiamato il metodo \#encrypt(String).encrypt(String); altrimenti, false.

**Restituisce:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Un valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password. Un valore false indica che l'intera presentazione crittografata viene caricata con l'uso della password corretta, non solo le proprietà del documento. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se PresentationEx.EncryptDocumentProperties è true, il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Booleano di sola lettura.

**Restituisce:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Restituisce un valore che indica se questa presentazione è protetta dalla scrittura. Booleano di sola lettura.

**Restituisce:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Restituisce la password di crittografia. Stringa di sola lettura.

**Restituisce:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Ottiene o imposta la raccomandazione di sola lettura. Booleano lettura/scrittura.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Restituisce:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Ottiene o imposta la raccomandazione di sola lettura. Booleano lettura/scrittura.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Cifra la presentazione con la password specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encryptionPassword | java.lang.String | La password. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Rimuove la crittografia.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Imposta la protezione dalla scrittura per questa presentazione con la password specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Rimuove la protezione dalla scrittura per questa presentazione.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Determina se una presentazione è protetta da password per la modifica.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password da verificare. |

1. È consigliabile verificare la proprietà (\#isWriteProtected.isWriteProtected) prima di chiamare questo metodo. 2. Quando la password è null o vuota, questo metodo restituisce false. |
**Restituisce:**
boolean - True se la password è valida; altrimenti, false.