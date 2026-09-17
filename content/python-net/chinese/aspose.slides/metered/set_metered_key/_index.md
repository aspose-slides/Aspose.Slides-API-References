---
title: set_metered_key method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
设置计量的公钥和私钥。
如果您购买了计量许可证，在启动应用程序时，应调用此 API，通常这就足够了。
但是，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态，
为避免这种情况，您应定期检查许可证状态，如果它是评估状态，请再次调用此 API。

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| public_key | **str** | 公钥 |
| private_key | **str** | 私钥 |

### 另见
* 类 [`Metered`](/slides/python-net/zh/aspose.slides/metered)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)