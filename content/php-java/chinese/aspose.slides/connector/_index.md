---
title: Connector
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/connector/
---
## Connector 类

  表示一个连接器。
 
### getConnectorLock {#getConnectorLock}

| 名称 | 描述 |
| --- | --- |
| getConnectorLock () | 返回连接器的锁。只读 IConnectorLock。 |

 **返回：**
[ConnectorLock](../connectorlock)


---


### getEndShapeConnectedTo {#getEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| getEndShapeConnectedTo () | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### getEndShapeConnectionSiteIndex {#getEndShapeConnectionSiteIndex}

| 名称 | 描述 |
| --- | --- |
| getEndShapeConnectionSiteIndex () | 返回或设置终端形状的连接点索引。可读写 long。 |

 **返回：**
long

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当值小于 EndShapeConnectedTo.ConnectionSiteCount 时抛出 |


---


### getShapeLock {#getShapeLock}

| 名称 | 描述 |
| --- | --- |
| getShapeLock () | 返回形状的锁。只读 IConnectorLock。 |

 **返回：**
[ConnectorLock](../connectorlock)


---


### getShapeType {#getShapeType}

| 名称 | 描述 |
| --- | --- |
| getShapeType () | 返回或设置 AutoShape 类型。可读写 ShapeType。 |

 **返回：**
int


---


### getStartShapeConnectedTo {#getStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| getStartShapeConnectedTo () | 返回或设置用于连接器起始端的形状。可读写 IShape。 |

 **返回：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### getStartShapeConnectionSiteIndex {#getStartShapeConnectionSiteIndex}

| 名称 | 描述 |
| --- | --- |
| getStartShapeConnectionSiteIndex () | 返回或设置起始形状的连接点索引。可读写 long。 |

 **返回：**
long

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当值小于 StartShapeConnectedTo.ConnectionSiteCount 时抛出 |


---


### reroute {#reroute}

| 名称 | 描述 |
| --- | --- |
| reroute () | 重新路由连接器，使其在所连接的形状之间走最短路径。 |

 **返回：**
void


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([GraphicalObject](../graphicalobject)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([Connector](../connector)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([Shape](../shape)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([SmartArtShape](../smartartshape)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([Table](../table)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([Ink](../ink)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([GeometryShape](../geometryshape)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([ZoomFrame](../zoomframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([VideoFrame](../videoframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([SmartArt](../smartart)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([GroupShape](../groupshape)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([InkActions](../inkactions)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([AutoShape](../autoshape)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([PictureFrame](../pictureframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([Chart](../chart)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([AudioFrame](../audioframe)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectedTo ([ZoomObject](../zoomobject)) | 返回或设置用于连接器末端的形状。可读写 IShape。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 为零) |


| setEndShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | 返回或设置将连接器的终点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setEndShapeConnectionSiteIndex {#setEndShapeConnectionSiteIndex}

| 名称 | 描述 |
| --- | --- |
| setEndShapeConnectionSiteIndex (long) | 返回或设置终点形状的连接点索引。读取/写入 long. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当值小于 EndShapeConnectedTo.ConnectionSiteCount 时抛出 |

---

### setShapeType {#setShapeType}

| 名称 | 描述 |
| --- | --- |
| setShapeType (int) | 返回或设置自动形状类型。读取/写入 ShapeType. |

**返回值:**
void

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([GraphicalObject](../graphicalobject)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([Connector](../connector)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([Shape](../shape)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([SmartArtShape](../smartartshape)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([Table](../table)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([Ink](../ink)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([GeometryShape](../geometryshape)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([ZoomFrame](../zoomframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([VideoFrame](../videoframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([SmartArt](../smartart)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([GroupShape](../groupshape)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([InkActions](../inkactions)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([AutoShape](../autoshape)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([PictureFrame](../pictureframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([Chart](../chart)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([AudioFrame](../audioframe)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([ZoomObject](../zoomobject)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | 返回或设置将连接器的起点附加到的形状。读取/写入 IShape. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当连接的形状没有任何连接点时抛出 (IShape.ConnectionSiteCount 等于零) |

---

### setStartShapeConnectionSiteIndex {#setStartShapeConnectionSiteIndex}

| 名称 | 描述 |
| --- | --- |
| setStartShapeConnectionSiteIndex (long) | 返回或设置起点形状的连接点索引。读取/写入 long. |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当值小于 StartShapeConnectedTo.ConnectionSiteCount 时抛出 |

---