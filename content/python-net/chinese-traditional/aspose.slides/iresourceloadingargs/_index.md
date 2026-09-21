---
title: IResourceLoadingArgs class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs 類別

外部資源載入參數的介面。

IResourceLoadingArgs 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`original_uri`](/slides/python-net/zh-hant/aspose.slides/iresourceloadingargs/original_uri/) | 匯入的簡報中指定的資源之原始 URI。 |
| [`uri`](/slides/python-net/zh-hant/aspose.slides/iresourceloadingargs/uri/) | 如果 **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** 返回 [`ResourceLoadingAction.DEFAULT`](/slides/python-net/zh-hant/aspose.slides/resourceloadingaction/DEFAULT)，則用於下載的資源 URI。<br/>            初始設定為資源的原始 URI，但可以重新定義為任何值。 |

## 方法

| Method | Description |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/zh-hant/aspose.slides/iresourceloadingargs/set_data/#bytes) | 設定使用者提供的資源資料，如果 **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            返回 [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/zh-hant/aspose.slides/resourceloadingaction/USER_PROVIDED)。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)