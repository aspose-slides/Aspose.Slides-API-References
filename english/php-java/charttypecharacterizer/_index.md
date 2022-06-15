---
title: ChartTypeCharacterizer
type: docs
weight: 0
url: /php-java/charttypecharacterizer/
---

# ChartTypeCharacterizer class

 Helper for getting additional information about charts and series by its ChartType.
 

## Constructors

| name | description |
| --- | --- |
| [ChartTypeCharacterizer](/slides/php-java/charttypecharacterizer/charttypecharacterizer/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [hasSeriesTrendLines](/slides/php-java/charttypecharacterizer/hasseriestrendlines/)(int) | boolean | Returns if there are series trend lines for specified series type. |
| [is2DChart](/slides/php-java/charttypecharacterizer/is2dchart/)(int) | boolean | Return true if chartType is one of 2D chart types. |
| [is3DChart](/slides/php-java/charttypecharacterizer/is3dchart/)(int) | boolean | Return true if chartType is one of 3D chart types. |
| [isBar3DChart](/slides/php-java/charttypecharacterizer/isbar3dchart/)(int) | boolean | Return true if chartType is one of bar3DChart subtypes (3D columns or bars). |
| [isChartTypeArea](/slides/php-java/charttypecharacterizer/ischarttypearea/)(int) | boolean | Return true if chartType is one of Area subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#Area, ChartType#PercentsStackedArea, ChartType#PercentsStackedArea3D, ChartType#StackedArea, ChartType#StackedArea3D, ChartType#Area3D. |
| [isChartTypeBar](/slides/php-java/charttypecharacterizer/ischarttypebar/)(int) | boolean | Return true if chartType is one of Bar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#ClusteredBar, ChartType#ClusteredBar3D, ChartType#PercentsStackedBar, ChartType#PercentsStackedBar3D, ChartType#StackedBar, ChartType#StackedBar3D, ChartType#ClusteredHorizontalCone, ChartType#ClusteredHorizontalCylinder, ChartType#ClusteredHorizontalPyramid, ChartType#StackedHorizontalCone, ChartType#StackedHorizontalCylinder, ChartType#StackedHorizontalPyramid, ChartType#PercentsStackedHorizontalCone, ChartType#PercentsStackedHorizontalCylinder, ChartType#PercentsStackedHorizontalPyramid. |
| [isChartTypeBubble](/slides/php-java/charttypecharacterizer/ischarttypebubble/)(int) | boolean | Return true if chartType is one of Bubble subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#Bubble, ChartType#BubbleWith3D. |
| [isChartTypeColumn](/slides/php-java/charttypecharacterizer/ischarttypecolumn/)(int) | boolean | Return true if chartType is one of Column subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#ClusteredColumn, ChartType#ClusteredColumn3D, ChartType#ClusteredCone, ChartType#ClusteredCylinder, ChartType#ClusteredPyramid, ChartType#PercentsStackedColumn, ChartType#PercentsStackedColumn3D, ChartType#PercentsStackedCone, ChartType#PercentsStackedCylinder, ChartType#PercentsStackedPyramid, ChartType#StackedColumn, ChartType#StackedColumn3D, ChartType#StackedCone, ChartType#StackedCylinder, ChartType#StackedPyramid, ChartType#Column3D, ChartType#Cylinder3D, ChartType#Cone3D, ChartType#Pyramid3D. |
| [isChartTypeDoughnut](/slides/php-java/charttypecharacterizer/ischarttypedoughnut/)(int) | boolean | Return true if chartType is one of Doughnut subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#Doughnut, ChartType#ExplodedDoughnut. |
| [isChartTypeLine](/slides/php-java/charttypecharacterizer/ischarttypeline/)(int) | boolean | Return true if chartType is one of Line subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#Line, ChartType#LineWithMarkers, ChartType#PercentsStackedLine, ChartType#PercentsStackedLineWithMarkers, ChartType#StackedLine, ChartType#StackedLineWithMarkers, ChartType#Line3D. |
| [isChartTypePie](/slides/php-java/charttypecharacterizer/ischarttypepie/)(int) | boolean | Return true if chartType is one of Pie subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#BarOfPie, ChartType#ExplodedPie, ChartType#ExplodedPie3D, ChartType#Pie, ChartType#Pie3D, ChartType#PieOfPie. |
| [isChartTypeRadar](/slides/php-java/charttypecharacterizer/ischarttyperadar/)(int) | boolean | Return true if chartType is one of Radar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#FilledRadar, ChartType#Radar, ChartType#RadarWithMarkers. |
| [isChartTypeScatter](/slides/php-java/charttypecharacterizer/ischarttypescatter/)(int) | boolean | Return true if chartType is one of Scatter subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#ScatterWithMarkers, ChartType#ScatterWithSmoothLines, ChartType#ScatterWithSmoothLinesAndMarkers, ChartType#ScatterWithStraightLines, ChartType#ScatterWithStraightLinesAndMarkers. |
| [isChartTypeStock](/slides/php-java/charttypecharacterizer/ischarttypestock/)(int) | boolean | Return true if chartType is one of Stock subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#HighLowClose, ChartType#OpenHighLowClose, ChartType#VolumeHighLowClose, ChartType#VolumeOpenHighLowClose. |
| [isChartTypeSurface](/slides/php-java/charttypecharacterizer/ischarttypesurface/)(int) | boolean | Return true if chartType is one of Surface subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see "Change Chart Type" dialog in PowerPoint): ChartType#Surface3D, ChartType#WireframeSurface3D, ChartType#Contour, ChartType#WireframeContour. |
| [isErrorBarsXAllowed](/slides/php-java/charttypecharacterizer/iserrorbarsxallowed/)(int) | boolean | Returns if error bars X allowed for specified series type. |
| [isErrorBarsYAllowed](/slides/php-java/charttypecharacterizer/iserrorbarsyallowed/)(int) | boolean | Returns if error bars Y allowed for specified series type. |
| [isSeriesUsesBubbleSizeCoordinate](/slides/php-java/charttypecharacterizer/isseriesusesbubblesizecoordinate/)(int) | boolean | Returns if bubble size coordinates can be used for specified series type. |
| [isSeriesUsesValueCoordinate](/slides/php-java/charttypecharacterizer/isseriesusesvaluecoordinate/)(int) | boolean | Returns if specified series type uses value coordinates. |
| [isSeriesUsesXValueCoordinate](/slides/php-java/charttypecharacterizer/isseriesusesxvaluecoordinate/)(int) | boolean | Returns if specified series type uses X value coordinates. |
| [isSeriesUsesYValueCoordinate](/slides/php-java/charttypecharacterizer/isseriesusesyvaluecoordinate/)(int) | boolean | Returns if specified series type uses Y value coordinates. |
