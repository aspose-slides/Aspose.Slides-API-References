---
title: Metered class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/metered/
---
## Metered 类

提供设置计量密钥的方法。

Metered 类型公开以下成员：

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/metered/__init__/#) | 初始化此类的新实例。 |

## Methods

| Method | Description |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/zh/aspose.slides/metered/set_metered_key/#str-str) | 设置计量公钥和私钥。<br/>            如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。 <br/>            然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态， <br/>            为避免此情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| [`get_consumption_quantity()`](/slides/python-net/zh/aspose.slides/metered/get_consumption_quantity/#) | 获取消耗文件大小 |
| [`get_consumption_credit()`](/slides/python-net/zh/aspose.slides/metered/get_consumption_credit/#) | 获取消耗积分 |
| [`get_product_name(self)`](/slides/python-net/zh/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/zh/aspose.slides/metered/is_metered_licensed/#) | 检查计量是否已授权 |


### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)