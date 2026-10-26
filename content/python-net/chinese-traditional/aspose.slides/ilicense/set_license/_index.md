---
title: set_license method
second_title: Aspose.Slides 的 Python 版 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
授權此元件。

```python
def set_license(self, license_name):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| license_name | **str** | 可以是完整或簡短的檔案名稱或嵌入資源的名稱。<br/><br/>使用空字串切換至評估模式。 |

### 備註

嘗試在以下位置尋找授權：

1. 明確路徑。

2. 元件組件所在的資料夾。

3. 客戶端呼叫組件的資料夾。

4. 入口組件的資料夾。

5. 客戶端呼叫組件中的嵌入資源。

**注意:** 在 .NET Compact Framework 上，僅嘗試在以下位置尋找授權：

1. 明確路徑。

2. 客戶端呼叫組件中的嵌入資源。

## set_license(self, stream) {#iorawiobase}
授權此元件。

```python
def set_license(self, stream):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 包含授權的資料流。 |

### 備註

使用此方法從資料流載入授權。

### 另見
* 類別 [`ILicense`](/slides/python-net/zh-hant/aspose.slides/ilicense)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)