---
title: IColorOperation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents different color operations used for color transformations.
type: docs
url: /hu/com.aspose.slides/icoloroperation/
---```
public interface IColorOperation
```

Különböző színműveleteket reprezentál, amelyeket színátalakításokhoz használnak.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOperationType()](#getOperationType--) | Visszaadja vagy beállítja egy művelet típusát. |
| [getParameter()](#getParameter--) | Visszaad egy paramétert egy műveletből. |
### getOperationType() {#getOperationType--}
```
public abstract int getOperationType()
```

Visszaadja vagy beállítja egy művelet típusát. Csak olvasható [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Visszatér:**  
int

### getParameter() {#getParameter--}
```
public abstract float getParameter()
```

Visszaad egy paramétert egy műveletből. Csak olvasható float.

**Visszatér:**  
float