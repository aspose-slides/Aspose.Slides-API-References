---
title: FontsLoader
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/fontsloader/
---
## FontsLoader 类

 用于加载用户定义的自定义字体的类。  
 应在创建任何演示文稿对象之前使用。

### clearCache {#clearCache}

| 名称 | 描述 |
| --- | --- |
| clearCache () | 释放用户定义的所有自定义字体。此方法需要清除用户定义的自定义字体缓存。 |

 **返回值:**
void


---


### getFontFolders {#getFontFolders}

| 名称 | 描述 |
| --- | --- |
| getFontFolders () | 获取字体文件夹。返回已通过 LoadExternalFonts 方法添加的文件夹以及系统字体文件夹 |

 **返回值:**
String


---


### loadExternalFont {#loadExternalFont}

| 名称 | 描述 |
| --- | --- |
| loadExternalFont (byte[]) | 从二进制数据添加字体 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 字体数据 |

 **返回值:**
void


---


### loadExternalFonts {#loadExternalFonts}

| 名称 | 描述 |
| --- | --- |
| loadExternalFonts (java.lang.String[]) | 添加额外的文件夹以搜索字体。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| directories | java.lang.String[] | 读取额外字体的目录。 |

 **返回值:**
void


---