---
title: VbaProject
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/vbaproject/
---
## VbaProject 类

 Represents VBA project with presentation macros.
 
### VbaProject {#VbaProject}

| 名称 | 描述 |
| --- | --- |
| VbaProject() | 此函数从头创建新的 VBA 项目。项目将使用 1252 Windows Latin 1 (ANSI) 代码页创建 |

 **返回:**  
VbaProject


---


### VbaProject {#VbaProject}

| 名称 | 描述 |
| --- | --- |
| VbaProject(byte[]) | 此函数从 OLE 容器的二进制表示加载 VBA 项目。 |

 **返回:**  
VbaProject


---


### getModules {#getModules}

| 名称 | 描述 |
| --- | --- |
| getModules () | 返回 VBA 项目中包含的所有模块的列表。只读 IVbaModuleCollection。 |

 **返回:**  
[VbaModuleCollection](../vbamodulecollection)


---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 返回 VBA 项目的名称。只读 String。 |

 **返回:**  
String


---


### getReferences {#getReferences}

| 名称 | 描述 |
| --- | --- |
| getReferences () | 返回 VBA 项目中包含的所有引用的列表。只读 IVbaReferenceCollection。 |

 **返回:**  
[VbaReferenceCollection](../vbareferencecollection)


---


### isPasswordProtected {#isPasswordProtected}

| 名称 | 描述 |
| --- | --- |
| isPasswordProtected () | 指示 VBAProject 是否受密码保护以查看项目属性。只读 boolean。 |

 **返回:**  
boolean


---


### toBinary {#toBinary}

| 名称 | 描述 |
| --- | --- |
| toBinary () | 返回 VBA 项目的二进制表示，作为 OLE 容器 |

 **返回:**  
byte


---