---
title: PresentationInfo
second_title: Riferimento API Java per Aspose.Slides per Android
description: Informazioni sul file di presentazione
type: docs
url: /it/com.aspose.slides/presentationinfo/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informazioni sul file di presentazione
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Restituisce True se la presentazione collegata è crittografata, altrimenti False. Boolean di sola lettura. |
| [isPasswordProtected()](#isPasswordProtected--) | Restituisce un valore che indica se la presentazione collegata è protetta da una password per l'apertura. |
| [isWriteProtected()](#isWriteProtected--) | Restituisce un valore che indica se la presentazione collegata è protetta da scrittura. |
| [getLoadFormat()](#getLoadFormat--) | Restituisce il formato della presentazione collegata. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Verifica se una password è corretta per una presentazione protetta da password di apertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Verifica se una password di modifica è corretta per una presentazione protetta da scrittura. |
| [readDocumentProperties()](#readDocumentProperties--) | Restituisce le proprietà del documento della presentazione collegata. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aggiorna le proprietà della presentazione collegata. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Scrive la presentazione collegata su stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Scrive la presentazione collegata su file. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Restituisce True se la presentazione collegata è crittografata, altrimenti False. Boolean di sola lettura.

**Restituisce:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Restituisce un valore che indica se la presentazione collegata è protetta da una password per l'apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Restituisce:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Restituisce un valore che indica se la presentazione collegata è protetta da scrittura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Se la presentazione è protetta da password per l'apertura, il valore della proprietà è uguale a NotDefined.

**Restituisce:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Restituisce il formato della presentazione collegata. Sola lettura [LoadFormat](../../com.aspose.slides/loadformat).

**Restituisce:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Verifica se una password è corretta per una presentazione protetta da password di apertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password da verificare. |

--------------------

Quando la password è null o vuota, questo metodo restituisce false. |

**Restituisce:**
boolean - True se la presentazione è protetta da password di apertura e la password è corretta e false altrimenti.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Verifica se una password di modifica è corretta per una presentazione protetta da scrittura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password da verificare. |

--------------------

1. Dovresti controllare la proprietà (\#isWriteProtected.isWriteProtected) prima di chiamare questo metodo. 2. Quando la password è null o vuota, questo metodo restituisce false. |

**Restituisce:**
boolean - True se la presentazione è protetta da scrittura e la password è corretta. False altrimenti.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Restituisce le proprietà del documento della presentazione collegata.

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aggiorna le proprietà della presentazione collegata.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Scrive la presentazione collegata su stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Lo stream deve essere ricercabile e scrivibile. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Scrive la presentazione collegata su file.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di presentazione. |