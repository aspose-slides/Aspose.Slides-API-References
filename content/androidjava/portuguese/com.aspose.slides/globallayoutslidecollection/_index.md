---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de todos os slides de layout na apresentação.
type: docs
url: /pt/com.aspose.slides/globallayoutslidecollection/
---
**Herança:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Representa uma coleção de todos os slides de layout na apresentação. Estende a classe LayoutSlideCollection com métodos para adicionar/clonar slides de layout no contexto de união das coleções individuais de slides mestres de layout.

## Métodos

| Método | Descrição |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adiciona um novo slide de layout à apresentação. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Adiciona uma cópia de um slide de layout especificado à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado. |

--------------------

Ao clonar um layout entre apresentações diferentes, o mestre do layout também pode ser clonado para manter a formatação de origem. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será nem impedida nem registrada. |

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Adiciona uma cópia de um slide de layout especificado à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para um novo layout. |

--------------------

1) O novo layout será vinculado ao mestre definido na apresentação de destino. Assim, este é análogo ao copiar/colar com a opção "Usar Tema de Destino" no PowerPoint. 2) Análoga a este método é o método [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) acessado com a propriedade ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Adiciona um novo slide de layout à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para um novo layout. |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout passado (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

--------------------

1) O layout adicionado para o valor SlideLayoutType.Custom de layoutType não contém espaços reservados nem formas. 2) Análoga a este método é o método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) acessado com a propriedade ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.