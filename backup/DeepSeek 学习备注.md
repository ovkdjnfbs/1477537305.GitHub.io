<img width="798" height="336" alt="Image" src="https://github.com/user-attachments/assets/d4808c16-bf24-47e9-8f71-40d5c2fe2c12" />

<img width="251" height="28" alt="Image" src="https://github.com/user-attachments/assets/611fc653-eb7f-4403-a394-61ffc3abc4ac" />

<img width="756" height="210" alt="Image" src="https://github.com/user-attachments/assets/fb541ff7-c493-49e5-a623-7164d9237bf6" />

<img width="387" height="151" alt="Image" src="https://github.com/user-attachments/assets/e0283aa5-f248-4d49-b6c0-3d796b4845ed" />

<img width="588" height="276" alt="Image" src="https://github.com/user-attachments/assets/479640f3-3c88-40d8-a3f3-3e9d211015da" />
<html xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:dt="uuid:C2F41010-65B3-11d1-A29F-00AA00C14882"
xmlns="http://www.w3.org/TR/REC-html40">

<head>

<meta name=ProgId content=OneNote.File>
<meta name=Generator content="Microsoft OneNote 15">
</head>

<body lang=zh-CN style='font-family:Calibri;font-size:11.0pt'>
<!--StartFragment-->

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>一、基础概念层</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>向量运算</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>点积（内积）</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>公式：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>a·b =
     Σ(aᵢbᵢ)</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>应用：计算夹角、投影（图形学光照计算）</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>叉积（三维）</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>公式：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>a×b =
     [a₂b₃-a₃b₂, a₃b₁-a₁b₃, a₁b₂-a₂b₁]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>应用：求平面法向量（3D建模）</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=2 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>矩阵基本操作</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>乘法规则<br>
          </span><span style='font-family:Menlo;font-size:10.0pt;background:
     #ECECEC'>Cᵢⱼ = Σ(AᵢₖBₖⱼ)</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>关键：仅当A列数=B行数时可乘</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>转置<br>
          </span><span style='font-family:Menlo;font-size:10.0pt;background:
     #ECECEC'>(Aᵀ)ᵢⱼ = Aⱼᵢ</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>应用：神经网络权重更新</span></li>
</ul>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>二、核心理论层</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>矩阵求逆</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>可逆条件：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>det(A) ≠ 0</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;color:#404040;background:white'>2×2矩阵公式：<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.0pt;
     color:#525252;background:white'>text<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.45pt;
     color:#494949;background:white'>A⁻¹ = (1/det(A)) * [d -b; -c a]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>应用：解线性方程组&nbsp;</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>Ax = b</span><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>&nbsp;→&nbsp;</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>x = A⁻¹b</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=2 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>行列式</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>几何意义：线性变换的缩放因子</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>计算方法：</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>2×2：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>det(A) = ad
     - bc</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>3×3：对角线法则（Sarrus规则）</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=3 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>特征值与特征向量</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>定义：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>Av = λv</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>求解步骤：</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     color:#404040'><span style='font-family:quote-cjk-patch;font-size:12.0pt;
     font-weight:normal;font-style:normal;font-family:quote-cjk-patch;
     font-size:12.0pt;background:white'>解特征方程&nbsp;</span><span
     style='font-family:Menlo;font-size:10.0pt;font-weight:normal;font-style:
     normal;font-family:Menlo;font-size:10.0pt;background:#ECECEC'>det(A - λI)
     = 0</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>对每个λ求</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>(A - λI)v =
     0</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>应用：PCA降维、物理系统稳定性分析</span></li>
</ul>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>三、几何应用层</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>线性变换</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;color:#404040;background:white'>旋转矩阵（2D）：<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.0pt;
     color:#525252;background:white'>text<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.45pt;
     color:#494949;background:white'>[cosθ -sinθ]<br>
          [sinθ<span style='mso-spacerun:yes'>  </span>cosθ]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;color:#404040;background:white'>缩放矩阵：<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.0pt;
     color:#525252;background:white'>text<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.45pt;
     color:#494949;background:white'>[sx<span style='mso-spacerun:yes'> 
     </span>0]<br>
          [0<span style='mso-spacerun:yes'>  </span>sy]</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=2 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>齐次坐标（图形学关键）</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>3D点表示为</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>[x, y, z, 1]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;color:#404040;background:white'>变换矩阵示例（平移）：<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.0pt;
     color:#525252;background:white'>text<br>
          </span><span style='font-family:quote-cjk-patch;font-size:9.45pt;
     color:#494949;background:white'>[1 0 0 tx]<br>
          [0 1 0 ty]<br>
          [0 0 1 tz]<br>
          [0 0 0 1]</span></li>
</ul>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>四、数值计算层</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>矩阵分解</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>LU分解：解方程组的高效方法</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>QR分解：最小二乘拟合</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>SVD分解：推荐系统、图像压缩</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=2 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>稀疏矩阵优化</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;margin-top:0pt;
     margin-bottom:3pt;line-height:21pt;color:#404040'><span style='font-family:
     quote-cjk-patch;font-size:12.0pt;background:white'>CSR存储格式：</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>非零值数组：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>data = [a,
     b, c, d]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>行指针：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>row_ptr =
     [0, 2, 3]</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>列索引：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>col_idx =
     [0, 1, 0]</span></li>
</ul>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>五、现代应用领域</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>计算机图形学</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>MVP矩阵：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>Model × View
     × Projection</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>法线变换：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>(M⁻¹)ᵀ·n</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=2 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>机器学习</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>梯度下降：</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>w = w -
     α(XᵀX)⁻¹Xᵀy</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>卷积运算：本质是稀疏矩阵乘法</span></li>
</ul>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=3 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     margin-top:0pt;margin-bottom:3pt;line-height:21pt;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;font-weight:normal;
     font-style:normal;font-family:quote-cjk-patch;font-size:12.0pt;background:
     white'>量子计算</span></li>
</ol>

<ul type=disc style='direction:ltr;unicode-bidi:embed;margin-top:0in;
 margin-bottom:0in'>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>量子门操作表示为酉矩阵（</span><span
     style='font-family:Menlo;font-size:10.0pt;background:#ECECEC'>U†U = I</span><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>）</span></li>
</ul>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>六、关键公式速查表</span></p>

<div style='direction:ltr'>


概念 | 公式 | 应用场景
-- | -- | --
点积 | a·b = \|a\|\|b\|cosθ | 光照计算
叉积模长 | \|a×b\| = \|a\|\|b\|sinθ | 计算平行四边形面积
矩阵迹 | tr(A) = ΣAᵢᵢ | 特征值求和
伴随矩阵 | adj(A) = Cᵀ (C为余子式矩阵) | 求逆矩阵



</div>

<p style='margin:0in;margin-left:.375in;font-family:Calibri;font-size:11.0pt'>&nbsp;</p>

<p style='margin-left:.375in;margin-top:13pt;margin-bottom:10pt;font-family:
quote-cjk-patch;font-size:13.7pt;color:#404040'><span style='background:white'>七、学习路径建议</span></p>

<ol type=1 style='direction:ltr;unicode-bidi:embed;margin-top:0in;margin-bottom:
 0in;font-family:Calibri;font-size:12.0pt;font-weight:normal;font-style:normal'>
 <li value=1 style='margin-top:0;margin-bottom:0;vertical-align:middle;
     color:#404040'><span style='font-family:quote-cjk-patch;font-size:12.0pt;
     font-weight:normal;font-style:normal;font-family:quote-cjk-patch;
     font-size:12.0pt;background:white'>入门：掌握2×2/3×3矩阵运算</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>进阶：理解秩、线性空间、基变换</span></li>
 <li style='margin-top:0;margin-bottom:0;vertical-align:middle;color:#404040'><span
     style='font-family:quote-cjk-patch;font-size:12.0pt;background:white'>高阶：学习张量运算（深度学习框架底层）</span></li>
</ol>

<p style='margin:0in;margin-left:.375in;font-size:11.0pt'><span
style='font-family:"Microsoft YaHei"'>这些知识点构成了从数学基础到工程应用的完整链条，建议通过实际编程（如</span><span
style='font-family:Calibri'>NumPy/SciPy</span><span style='font-family:"Microsoft YaHei"'>）深化理解。</span></p>

<!--EndFragment-->
</body>

</html>
