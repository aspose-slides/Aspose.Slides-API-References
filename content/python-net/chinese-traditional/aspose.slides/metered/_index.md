---
title: Metered class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/metered/
---
## Metered 類別

提供設定計量金鑰的方法。

Metered 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/metered/__init__/#) | 初始化此類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/zh-hant/aspose.slides/metered/set_metered_key/#str-str) | 設定計量的公鑰與私鑰。<br/>如果您購買計量授權，應在應用程式啟動時呼叫此 API，通常這即可。<br/>然而，如果始終無法上傳消耗資料且超過 24 小時，授權將被設定為評估狀態，<br/>為避免此情況，您應定期檢查授權狀態，若為評估狀態，請再次呼叫此 API。 |
| [`get_consumption_quantity()`](/slides/python-net/zh-hant/aspose.slides/metered/get_consumption_quantity/#) | 取得消耗檔案大小 |
| [`get_consumption_credit()`](/slides/python-net/zh-hant/aspose.slides/metered/get_consumption_credit/#) | 取得消耗點數 |
| [`get_product_name(self)`](/slides/python-net/zh-hant/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/zh-hant/aspose.slides/metered/is_metered_licensed/#) | 檢查計量是否已授權 |


### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)