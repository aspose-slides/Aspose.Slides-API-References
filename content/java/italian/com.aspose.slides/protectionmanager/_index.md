---
title: ProtectionManager
second_title: Riferimento API di Aspose.Slides per Java
description: Gestione della protezione con password della presentazione.
type: docs
url: /it/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Gestione della protezione con password della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Questa proprietà ha senso, se la presentazione è protetta da password. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Questa proprietà ha senso, se la presentazione è protetta da password. |
| [isEncrypted()](#isEncrypted--) | Restituisce un valore che indica se questa istanza è crittografata. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. |
| [isWriteProtected()](#isWriteProtected--) | Restituisce un valore che indica se questa presentazione è protetta da scrittura. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Crittografa la presentazione con la password specificata. |
| [removeEncryption()](#removeEncryption--) | Rimuove la crittografia. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Imposta la protezione da scrittura per questa presentazione con la password specificata. |
| [removeWriteProtection()](#removeWriteProtection--) | Rimuove la protezione da scrittura per questa presentazione. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina se una presentazione è protetta da password per la modifica. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Restituisce la password usata per la crittografia della presentazione. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Restituisce o imposta la raccomandazione di sola lettura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Restituisce o imposta la raccomandazione di sola lettura. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Questa proprietà ha senso, se la presentazione è protetta da password. Se true allora le proprietà del documento sono crittografate nel file della presentazione. Se false allora le proprietà del documento sono pubbliche mentre la presentazione è crittografata. Boolean di lettura/scrittura.

**Returns:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Questa proprietà ha senso, se la presentazione è protetta da password. Se true allora le proprietà del documento sono crittografate nel file della presentazione. Se false allora le proprietà del documento sono pubbliche mentre la presentazione è crittografata. Boolean di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Restituisce un valore che indica se questa istanza è crittografata. Boolean di sola lettura.

Valore: true se la presentazione è stata caricata da un file crittografato o se è stato chiamato il metodo \#encrypt(String).encrypt(String); altrimenti, false.

**Returns:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Un valore true indica che solo le proprietà del documento sono caricate da un file di presentazione crittografato senza l'uso della password. Un valore false indica che l'intera presentazione crittografata è caricata con l'uso della password corretta, non solo le proprietà del documento. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se Presentation.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Boolean di sola lettura.

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Restituisce un valore che indica se questa presentazione è protetta da scrittura. Boolean di sola lettura.

**Returns:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Crittografa la presentazione con la password specificata.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encryptionPassword | java.lang.String | La password. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Rimuove la crittografia.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Imposta la protezione da scrittura per questa presentazione con la password specificata.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Rimuove la protezione da scrittura per questa presentazione.

--------------------

> ```
> Questo esempio di codice mostra come rimuovere la protezione da scrittura da una presentazione PowerPoint.
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
| password | java.lang.String | La password per la verifica.

--------------------

1. Dovresti verificare la proprietà (\#isWriteProtected.isWriteProtected) prima di chiamare questo metodo. 2. Quando la password è null o vuota, questo metodo restituisce false. |
**Returns:**
boolean - True se la password è valida; altrimenti, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Restituisce la password usata per la crittografia della presentazione. String di sola lettura.

**Returns:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Restituisce o imposta la raccomandazione di sola lettura. Boolean di lettura/scrittura.

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

**Returns:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Restituisce o imposta la raccomandazione di sola lettura. Boolean di lettura/scrittura.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |