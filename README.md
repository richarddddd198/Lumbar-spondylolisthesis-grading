# 腰椎辅助诊断系统之滑脱定位并分级(基于paddleseg)
### 背景

#### 【什么是滑脱】

腰椎滑脱 是由于先天性发育不良、创伤、劳损等原因造成相邻椎体骨性连接异常而发生的上位椎体与下位椎体部分或全部滑移，表现为腰骶部疼痛、坐骨神经受累、间歇性跛行等症状的疾病。

在所有的腰椎滑脱中，由峡部崩裂引起的滑脱约占15%，退行性腰椎滑脱约占35%。在我国腰椎滑脱的发病年龄多在20~50岁，占85%；男性明显多于女性，男女之比为 29：1。腰椎滑脱最常见的部位是 L4~L5 及 L5~S1，其中腰5椎体发生率为82~90% 。滑脱的椎体可引起或加重椎管狭窄，刺激或挤压神经，引起腰痛、下肢痛、下肢麻木、甚至大小便功能障碍等症状。另外，滑脱后腰背肌的保护性收缩可引起腰背肌劳损，产生腰背痛。

可以通过X光检查、CT检查、MR检查进行诊断。以腰椎的侧位方向观察为佳。

#### 【滑脱的分级】

国内常用的是 Meyerding 分级，即将下位椎体上缘分为 4 等份，根据椎体相对下位椎 体向前滑移的程度分为 I－IV 度。(如下图)

Ⅰ：指椎体向前滑动不超过椎体中部矢状径的 1/4 者。

Ⅱ ：超过 1/4，但不超过 2/4 者。

Ⅲ ：超过 2/4，但不超过 3/4 者。

Ⅳ ：超过椎体矢状径的 3/4 者。
 
#### 【项目的目的】

腰椎的MR检查是一种无创检查。对腰椎的软组织、椎间盘、脊髓等组织的观察有优势。目前想通过腰椎MR检查的图像结合人工智能进行多种腰椎疾病辅助诊断，减少医生的负担。因为腰椎滑脱是一种常见的腰椎疾病，所有这个项目通过分割来解决腰椎滑脱分级这个问题。
![image](https://github.com/richarddddd198/Lumbar-spondylolisthesis-grading/blob/main/1.png)

#### 【项目最终分级结果】

推理过程是基于诊断腰椎滑脱Meyerding标准。推理结果基本是符合腰椎滑脱的影像诊断要求。

![image](https://github.com/richarddddd198/Lumbar-spondylolisthesis-grading/blob/main/result.png)
