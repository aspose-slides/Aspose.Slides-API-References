---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create presentation via COM interface
type: docs
weight: 988
url: /androidjava/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Allows to create presentation via COM interface
## Methods

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Gets info about presentation in specified file. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Gets info about presentation in specified stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Creates new presentation.

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - New presentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```


Gets info about presentation in specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Presentation file. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentation info
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Gets info about presentation in specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Presentation stream. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentation info.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
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
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
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
public abstract IPresentation readPresentation(InputStream stream)
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
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
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
public abstract IPresentation readPresentation(String file)
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
public abstract IPresentation readPresentation(String file, ILoadOptions options)
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
public abstract IPresentationText getPresentationText(String file, int mode)
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
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
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
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
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
