---
title: AppendFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: 將格式化字串附加至建構器。
type: docs
weight: 131
url: /zh-hant/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) 方法

將格式化字串附加到建構器。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TArgs | 參數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)& | 格式字串。 |
| args | const TArgs&... | 插入至格式字串位置的引數。 |

### 返回值

此指標。

## StringBuilder::AppendFormat(const SharedPtr<IFormatProvider>&, const String&, const TArgs&...) 方法

將格式化字串附加到建構器。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TArgs | 參數類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)<[IFormatProvider](../../../system/iformatprovider/)>& | 格式提供者；已忽略。 |
| format | const [String](../../../system/string/)& | 格式字串。 |
| args | const TArgs&... | 插入至格式字串位置的引數。 |

### 返回值

此指標。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [StringBuilder](../)
* 類別 [String](../../../system/string/)
* 類別 [IFormatProvider](../../../system/iformatprovider/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)