---
title: PresentationInfo
second_title: Aspose.Slides för Android via Java API-referens
description: Information om presentationsfil
type: docs
url: /sv/com.aspose.slides/presentationinfo/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Information om presentationsfil
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Returnerar True om den bundna presentationen är krypterad, annars False. |
| [isPasswordProtected()](#isPasswordProtected--) | Returnerar ett värde som anger om den bundna presentationen är skyddad med ett lösenord för att öppna. |
| [isWriteProtected()](#isWriteProtected--) | Returnerar ett värde som anger om den bundna presentationen är skrivskyddad. |
| [getLoadFormat()](#getLoadFormat--) | Returnerar formatet för den bundna presentationen. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kontrollerar om ett lösenord är korrekt för en presentation skyddad med öppningslösenord. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kontrollerar om ett ändringslösenord är korrekt för en skrivskyddad presentation. |
| [readDocumentProperties()](#readDocumentProperties--) | Returnerar dokumentegenskaper för den bundna presentationen. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Uppdaterar egenskaper för den bundna presentationen. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Skriver den bundna presentationen till en ström. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Skriver den bundna presentationen till en fil. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Returnerar True om den bundna presentationen är krypterad, annars False. Skrivskyddad boolean.

**Returnerar:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Returnerar ett värde som anger om den bundna presentationen är skyddad med ett lösenord för att öppna.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Returnerar ett värde som anger om den bundna presentationen är skrivskyddad.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Om presentationen är skyddad med ett lösenord för att öppna, är egenskapsvärdet lika med NotDefined.

**Returnerar:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Returnerar formatet för den bundna presentationen. Skrivskyddad [LoadFormat](../../com.aspose.slides/loadformat).

**Returnerar:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Kontrollerar om ett lösenord är korrekt för en presentation skyddad med öppningslösenord.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
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
public final boolean checkWriteProtection(String password)
```

Kontrollerar om ett lösenord för ändring är korrekt för en skrivskyddad presentation.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
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

1. Du bör kontrollera (\#isWriteProtected.isWriteProtected) egenskapen innan du anropar denna metod. 2. När lösenordet är null eller tomt, returnerar denna metod false. |

**Returnerar:**
boolean - True om presentationen är skrivskyddad och lösenordet är korrekt. False annars.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Returnerar dokumentegenskaper för den bundna presentationen.

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Skriver den bundna presentationen till en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen måste vara sökbar och skrivbar. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Skriver den bundna presentationen till en fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Presentationsfil. |