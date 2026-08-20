---
title: IPresentationFactory
second_title: Aspose.Slides for Java API 參考文件
description: 允許透過 COM 介面建立簡報
type: docs
url: /zh-hant/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

允許透過 COM 介面建立簡報

## 方法

| 方法 | 說明 |
| --- | --- |
| [createPresentation()](#createPresentation--) | 建立新的簡報。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 建立新的簡報，包含額外的載入選項 |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | 取得指定檔案中簡報的資訊。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | 取得指定串流中簡報的資訊。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 從陣列讀取現有的簡報 |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 從陣列讀取現有的簡報，並使用額外的載入選項 |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | 從串流讀取現有的簡報 |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 從串流讀取現有的簡報，並使用額外的載入選項 |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | 從檔案讀取現有的簡報 |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 從串流讀取現有的簡報，並使用額外的載入選項 |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | 取得投影片的原始文字 |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | 取得投影片的原始文字 |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | 取得投影片的原始文字 |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

建立新的簡報。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新的簡報

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

建立新的簡報，並使用額外的載入選項

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 新的簡報

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

取得指定檔案中簡報的資訊。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 簡報檔案。 |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 簡報資訊

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

取得指定串流中簡報的資訊。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 簡報串流。 |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 簡報資訊。

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

從陣列讀取現有的簡報

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 要讀取的陣列 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

從陣列讀取現有的簡報，並使用額外的載入選項

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 要讀取的陣列 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

從串流讀取現有的簡報

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要讀取的輸入串流 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

從串流讀取現有的簡報，並使用額外的載入選項

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要讀取的輸入串流 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

從檔案讀取現有的簡報

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 檔案名稱 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

從串流讀取現有的簡報，並使用額外的載入選項

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 檔案名稱 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - 已讀取的簡報

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

取得投影片的原始文字

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 輸入檔案 |
| mode | int | 抽取模式 |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 此 PresentationText 實例包含表示投影片原始文字的 SlideText 陣列

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

取得投影片的原始文字

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入串流 |
| mode | int | 抽取模式 |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 此 PresentationText 實例包含表示投影片原始文字的 SlideText 陣列

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

取得投影片的原始文字

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入串流 |
| mode | int | 抽取模式 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 此 PresentationText 實例包含表示投影片原始文字的 SlideText 陣列