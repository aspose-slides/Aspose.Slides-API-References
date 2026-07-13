---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /sv/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Information om presentationsfil
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Returnerar True om den bundna presentationen är krypterad, annars False. |
| [isPasswordProtected()](#isPasswordProtected--) | Returnerar ett värde som anger om den bundna presentationen är skyddad med ett lösenord för öppning. |
| [isWriteProtected()](#isWriteProtected--) | Returnerar ett värde som anger om den bundna presentationen är skrivskyddad. |
| [getLoadFormat()](#getLoadFormat--) | Returnerar formatet på den bundna presentationen. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppningslösenord. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kontrollerar om ett lösenord för ändring är korrekt för en skrivskyddad presentation. |
| [readDocumentProperties()](#readDocumentProperties--) | Returnerar dokumentegenskaper för den bundna presentationen. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Uppdaterar egenskaper för den bundna presentationen. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Skriver den bundna presentationen till en ström. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Skriver den bundna presentationen till en fil. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Returnerar True om den bundna presentationen är krypterad, annars False. Skrivskyddad boolesk.

**Returnerar:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Returnerar ett värde som anger om den bundna presentationen är skyddad med ett lösenord för öppning.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Returnerar ett värde som anger om den bundna presentationen är skrivskyddad.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Om presentationen är skyddad med ett lösenord för öppning, är egenskapsvärdet lika med NotDefined. Se [NullableBool](../../com.aspose.slides/nullablebool)-enumerationen.

**Returnerar:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Returnerar formatet på den bundna presentationen. Skrivskyddad [LoadFormat](../../com.aspose.slides/loadformat).

**Returnerar:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppningslösenord.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | java.lang.String | Lösenordet att kontrollera. |

--------------------

När lösenordet är null eller tomt, returnerar denna metod false. |

**Returnerar:**
boolean - True om presentationen är skyddad med öppningslösenord och lösenordet är korrekt, annars false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Kontrollerar om ett lösenord för ändring är korrekt för en skrivskyddad presentation.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | java.lang.String | Lösenordet att kontrollera. |

--------------------

1. Du bör kontrollera (\#isWriteProtected.isWriteProtected)-egenskapen innan du anropar denna metod. 2. När lösenordet är null eller tomt, returnerar denna metod false. |

**Returnerar:**
boolean - True om presentationen är skrivskyddad och lösenordet är korrekt. False annars.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Returnerar dokumentegenskaper för den bundna presentationen.

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - dokumentegenskaper [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Uppdaterar egenskaper för den bundna presentationen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | dokumentegenskaper [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Skriver den bundna presentationen till en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen måste vara sökbar och skrivbar. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Skriver den bundna presentationen till en fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Presentationsfil. |