---
title: TemplateContext
second_title: 通过 Java API 的 Aspose.Sildes for PHP 参考
description: 
type: docs

url: /zh/aspose.slides/templatecontext/
---
## TemplateContext 类

表示模板引擎的模型对象接口。

### getGlobal {#getGlobal}

| 名称 | 描述 |
| --- | --- |
| getGlobal () | 返回主文档的全局存储。只读 Storage。 |

**返回：**
Storage

---


### getLocal {#getLocal}

| 名称 | 描述 |
| --- | --- |
| getLocal () | 返回当前模板上下文的本地存储。只读 Storage。 |

**返回：**
Storage

---


### getObject {#getObject}

| 名称 | 描述 |
| --- | --- |
| getObject () | 返回模型对象。只读 Object。 |

**返回：**
TObject

---


### getOutput {#getOutput}

| 名称 | 描述 |
| --- | --- |
| getOutput () | 返回主文档的输出元素集合。只读 Output( #getOutput)。 |

**返回：**
Output

---


### subModel {#subModel}

| 名称 | 描述 |
| --- | --- |
| subModel (TSubModel) | 创建子模板上下文。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| subModel | TSubModel | 子模型对象。 |

**返回：**
TemplateContext

---