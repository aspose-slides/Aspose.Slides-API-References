---
title: License
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/license/
---
## License 类
提供用于授权组件的方法。

 在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

### License {#License}

| 名称 | 描述 |
| --- | --- |
| License() | 初始化此类的新实例。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 |

**返回：**
License

---

### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () | 返回 Aspose.Slides for Java 的版本。 |

**返回：**
String

---

### isLicensed {#isLicensed}

| 名称 | 描述 |
| --- | --- |
| isLicensed () |  |

**返回：**
boolean

---

### resetLicense {#resetLicense}

| 名称 | 描述 |
| --- | --- |
| resetLicense () | 重置许可证。使用此方法可在组件中重置许可证。 |

**返回：**
void

---

### setLicense {#setLicense}

| 名称 | 描述 |
| --- | --- |
| setLicense (InputStream) | 为组件授权。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 包含许可证的流。使用 null 可切换到评估模式。 |

**返回：**
void

---

### setLicense {#setLicense}

| 名称 | 描述 |
| --- | --- |
| setLicense (String) | 为组件授权。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| namePath | String | 可以是完整或简短的文件名或嵌入资源的名称。使用空字符串可切换到评估模式。 |

**返回：**
void

---