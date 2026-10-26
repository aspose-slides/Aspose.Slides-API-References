---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许通过 COM 接口创建演示文稿
type: docs
url: /zh/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

允许通过 COM 接口创建演示文稿
## 方法

| 方法 | 描述 |
| --- | --- |
| [createPresentation()](#createPresentation--) | 创建新演示文稿。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 使用附加加载选项创建新演示文稿 |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | 获取指定文件中演示文稿的信息。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | 获取指定流中演示文稿的信息。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 从数组读取现有演示文稿 |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 使用附加加载选项从数组读取现有演示文稿 |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | 从流读取现有演示文稿 |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 使用附加加载选项从流读取现有演示文稿 |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | 从文件读取现有演示文稿 |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 使用附加加载选项从流读取现有演示文稿 |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | 检索幻灯片的原始文本 |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | 检索幻灯片的原始文本 |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | 检索幻灯片的原始文本 |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

创建新演示文稿。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新演示文稿
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

使用附加加载选项创建新演示文稿

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新演示文稿
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

获取指定文件中演示文稿的信息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 演示文稿文件。 |

**返回:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 演示文稿信息
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

获取指定流中演示文稿的信息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 演示文稿流。 |

**返回:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 演示文稿信息。
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

从数组读取现有演示文稿

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 待读取的数组 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

从数组读取现有演示文稿并使用附加加载选项

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 待读取的数组 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

从流读取现有演示文稿

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 待读取的输入流 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

从流读取现有演示文稿并使用附加加载选项

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 待读取的输入流 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

从文件读取现有演示文稿

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件名 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

使用附加加载选项从流读取现有演示文稿

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 文件名 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已读取的演示文稿
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

检索幻灯片的原始文本

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 输入文件 |
| mode | int | 提取模式 |

**返回:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含 SlideText 数组的 PresentationText 实例，表示原始幻灯片文本
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

检索幻灯片的原始文本

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流 |
| mode | int | 提取模式 |

**返回:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含 SlideText 数组的 PresentationText 实例，表示原始幻灯片文本
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

检索幻灯片的原始文本

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流 |
| mode | int | 提取模式 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 加载选项 |

**返回:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含 SlideText 数组的 PresentationText 实例，表示原始幻灯片文本