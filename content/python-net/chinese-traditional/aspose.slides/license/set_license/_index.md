---
title: set_license method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
為元件授權。

```python
def set_license(self, license_name):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| license_name | **str** | 可以是完整或簡短的檔案名稱，或是嵌入式資源的名稱。<br/><br/>            使用空字串以切換至評估模式。 |

### 備註

嘗試在以下位置尋找授權：

1. 明確路徑。
2. 元件組件的資料夾。
3. 客戶端呼叫組件的資料夾。
4. 入口組件的資料夾。
5. 客戶端呼叫組件中的嵌入式資源。

**注意:** 在 .NET Compact Framework 上，只會在以下位置尋找授權：

1. 明確路徑。
2. 客戶端呼叫組件中的嵌入式資源。

## set_license(self, stream) {#iorawiobase}
為元件授權。

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
* 類別 [`License`](/slides/python-net/zh-hant/aspose.slides/license)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)