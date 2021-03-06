---
title: SetSubSuperscriptOnTheRight
second_title: Aspose.Slides for .NET API 参考
description: 在右边创建下标和上标
type: docs
weight: 160
url: /zh/net/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## SetSubSuperscriptOnTheRight(IMathElement, IMathElement) {#setsubsuperscriptontheright}

在右边创建下标和上标

```csharp
public IMathRightSubSuperscriptElement SetSubSuperscriptOnTheRight(IMathElement subscript, 
    IMathElement superscript)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| subscript | IMathElement | 下标（右下标） |
| superscript | IMathElement | 上标（右上方的索引） |

### 返回值

类型的新数学元素[`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)

### 例子

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("N");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight(subscript, superscript);
```

### 也可以看看

* interface [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* interface [IMathElement](../../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../imathelement)
* 部件 [Aspose.Slides](../../../)

---

## SetSubSuperscriptOnTheRight(string, string) {#setsubsuperscriptontheright_1}

在右边创建下标和上标

```csharp
public IMathRightSubSuperscriptElement SetSubSuperscriptOnTheRight(string subscript, 
    string superscript)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| subscript | String | 下标（右下标） |
| superscript | String | 上标（右上方的索引） |

### 返回值

类型的新数学元素[`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)

### 例子

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("N");
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight("i", "j");
```

### 也可以看看

* interface [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* interface [IMathElement](../../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../imathelement)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
