---
title: IPresentationInfo
second_title: Aspose.Slides per Android via Java API Reference
description: Informazioni sul file di presentazione
type: docs
url: /it/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informazioni sul file di presentazione
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Restituisce True se la presentazione collegata è crittografata, altrimenti False. |
| [isPasswordProtected()](#isPasswordProtected--) | Restituisce un valore che indica se la presentazione collegata è protetta da una password per l'apertura. |
| [isWriteProtected()](#isWriteProtected--) | Restituisce un valore che indica se la presentazione collegata è protetta in scrittura. |
| [getLoadFormat()](#getLoadFormat--) | Restituisce il formato della presentazione collegata. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Verifica se una password è corretta per una presentazione protetta da password di apertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Verifica se una password di modifica è corretta per una presentazione protetta in scrittura. |
| [readDocumentProperties()](#readDocumentProperties--) | Restituisce le proprietà del documento della presentazione collegata. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aggiorna le proprietà della presentazione collegata. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Scrive la presentazione collegata su stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Scrive la presentazione collegata su file. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Restituisce True se la presentazione collegata è crittografata, altrimenti False. Solo lettura boolean.

**Restituisce:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Restituisce un valore che indica se la presentazione collegata è protetta da una password per l'apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Restituisce:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Restituisce un valore che indica se la presentazione collegata è protetta in scrittura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Se la presentazione è protetta da una password per l'apertura, il valore della proprietà è uguale a NotDefined. Vedi l'enumerazione [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Restituisce il formato della presentazione collegata. Solo lettura [LoadFormat](../../com.aspose.slides/loadformat).

**Restituisce:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Verifica se una password è corretta per una presentazione protetta da password di apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password da verificare. |

Quando la password è null o vuota, questo metodo restituisce false.

**Restituisce:**
boolean - True se la presentazione è protetta da password di apertura e la password è corretta, false altrimenti.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Verifica se una password di modifica è corretta per una presentazione protetta in scrittura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password da verificare. |

1. È necessario verificare la proprietà (\#isWriteProtected.isWriteProtected) prima di chiamare questo metodo. 2. Quando la password è null o vuota, questo metodo restituisce false.

**Restituisce:**
boolean - True se la presentazione è protetta in scrittura e la password è corretta. False altrimenti.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Restituisce le proprietà del documento della presentazione collegata.

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Proprietà del documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aggiorna le proprietà della presentazione collegata.

--------------------

> ```
> Questo esempio mostra come chiamare il metodo #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) per
>  aggiornare le proprietà del documento restituite dalla chiamata al metodo #readDocumentProperties.readDocumentProperties.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Proprietà del documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Scrive la presentazione collegata su stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Lo stream deve essere ricercabile e scrivibile. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Scrive la presentazione collegata su file.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di presentazione. |