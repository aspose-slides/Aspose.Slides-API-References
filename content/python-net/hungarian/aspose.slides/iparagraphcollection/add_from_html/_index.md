---
title: add_from_html method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
A megadott HTML karakterláncból szöveget ad hozzá a gyűjteményhez.


```python
def add_from_html(self, text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| text | **str** | HTML szöveg. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
A megadott HTML karakterláncból szöveget ad hozzá a gyűjteményhez.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| text | **str** | HTML szöveg. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Feltétel visszahívás objektum, amely feloldja az URI-kat és letölti a hivatkozott objektumokat. |
| uri | **str** | URI a HTML dokumentum hozzáadásához. Relatív hivatkozások feloldására használatos. |

### Megjegyzés

A resolver megadása potenciálisan sebezhetőséget okozhat. Óvatosan használja.



### Lásd még
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`IParagraphCollection`](/slides/python-net/hu/aspose.slides/iparagraphcollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)