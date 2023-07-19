---
title: PresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create presentation via COM interface
type: docs
weight: 451
url: /java/com.aspose.slides/presentationfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Allows to create presentation via COM interface

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory static instance. |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Creates new PresentationInfo object from stream and binds presentation to it. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Presentation factory static instance. Read-only [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Returns:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Creates new presentation.

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - New presentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Creates new presentation with additional load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Load options |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - New presentation
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Creates new PresentationInfo object from file and binds presentation to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Presentation file. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentation info binded to presentation.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Presentation stream. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentation info binded to presentation.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


Reads an existing presentation from array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Array to read |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Reads an existing presentation from array with additional load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Array to read |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Load options |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Reads an existing presentation from stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream to read |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Reads an existing presentation from stream with additional load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream to read |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Load options |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


Reads an existing presentation from file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | File name |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Reads an existing presentation from stream with additional load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | File name |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Load options |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Read presentation
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Retrieves the raw text from the slides

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Input file |
| mode | int | Extraction mode |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - The instance of PresentationText containing the SlideText array representing the raw slides text
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Retrieves the raw text from the slides

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream |
| mode | int | Extraction mode |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - The instance of PresentationText containing the SlideText array representing the raw slides text
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Retrieves the raw text from the slides

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream |
| mode | int | Extraction mode |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Load options |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - The instance of PresentationText containing the SlideText array representing the raw slides text
