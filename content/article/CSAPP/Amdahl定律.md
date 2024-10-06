---
title: Amdahl定律
date: 2024-10-06
description: 
summary: 
tags:
  - blog
lastmod: 2024-10-06T13:20:10.499Z
---
对系统的某个部分提升时，其对系统整体性能的影响取决于该部分的重要性和提升程度。

假设系统执行某个应用程序的时间为 $T_{old}$ ，该应用程序某部分的执行时间与该时间的比例为 $\alpha$，现在针对该部分进行提升的比例为 k，则加速比 $S = T_{old} / T_{new}$

$S=\frac{1}{(1-\alpha)+\frac{\alpha}{k}}$
