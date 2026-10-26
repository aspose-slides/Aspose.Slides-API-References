---
title: IResourceLoadingArgs class
second_title: Aspose.Slides a Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs osztály

Külső erőforrás betöltési argumentumokhoz való interfész.

Az IResourceLoadingArgs típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`original_uri`](/slides/python-net/hu/aspose.slides/iresourceloadingargs/original_uri/) | Az erőforrás eredeti URI-ja, ahogy az importált prezentációban van megadva. |
| [`uri`](/slides/python-net/hu/aspose.slides/iresourceloadingargs/uri/) | Az erőforrás URI-ja, amelyet a letöltéshez használnak, ha **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.DEFAULT`](/slides/python-net/hu/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Kezdetben az erőforrás eredeti URI-jára van beállítva, de bármilyen értékre újra definiálható. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/hu/aspose.slides/iresourceloadingargs/set_data/#bytes) | Beállítja a felhasználó által megadott adatokat az erőforráshoz, amelyet akkor használnak, ha **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/hu/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)