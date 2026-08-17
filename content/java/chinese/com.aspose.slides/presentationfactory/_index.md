---
title: PresentationFactory
second_title: Aspose.Slides for Java API 参考
description: 允许通过 COM 接口创建演示文稿
type: docs
url: /zh/com.aspose.slides/presentationfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

允许通过 COM 接口创建演示文稿

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation 工厂的静态实例。 |
| [createPresentation()](#createPresentation--) | 创建新的演示文稿。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 创建带有附加加载选项的新演示文稿 |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | 从文件创建新的 PresentationInfo 对象并将演示文稿绑定到其上。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | 从流创建新的 PresentationInfo 对象并将演示文稿绑定到其上。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 从数组读取现有演示文稿 |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 从数组读取现有演示文稿，带有附加加载选项 |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | 从流读取现有演示文稿 |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 从流读取现有演示文稿，带有附加加载选项 |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | 从文件读取现有演示文稿 |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 从流读取现有演示文稿，带有附加加载选项 |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | 检索幻灯片的原始文本 |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | 检索幻灯片的原始文本 |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | 检索幻灯片的原始文本 |

### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Presentation 工厂的静态实例。只读 [PresentationFactory](../../com.aspose.slides/presentationfactory)。

**返回：**
[PresentationFactory](../../com.aspose.slides/presentationfactory)

### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

创建新的演示文稿。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 新建演示文稿

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

创建带有附加加载选项的新演示文稿

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 新建演示文稿

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

从文件创建新的 PresentationInfo 对象并将演示文稿绑定到其上。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 演示文稿文件。 |

**返回：**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 与演示文稿绑定的 PresentationInfo

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

从流创建新的 PresentationInfo 对象并将演示文稿绑定到其上。获取指定流中演示文稿的信息。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 演示文稿流。 |

**返回：**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 与演示文稿绑定的 PresentationInfo

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPPresentation readPresentation(byte[] data)
```

从数组读取现有演示文稿

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 要读取的数组 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

从数组读取现有演示文稿，带有附加加载选项

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 要读取的数组 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

从流读取现有演示文稿

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要读取的输入流 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

从流读取现有演示文稿，带有附加加载选项

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要读取的输入流 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

从文件读取现有演示文稿

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件名 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPPresentation readPresentation(String file, ILoadOptions options)
```

从文件读取现有演示文稿，带有附加加载选项

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件名 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

检索幻灯片的原始文本

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 输入文件 |
| mode | int | 提取模式 |

**返回：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPPresentationText getPresentationText(InputStream stream, int mode)
```

检索幻灯片的原始文本

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流 |
| mode | int | 提取模式 |

**返回：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

检索幻灯片的原始文本

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流 |
| mode | int | 提取模式 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例