# Notes Repository / 笔记仓库

Bilingual study-notes archive: PDFs exported from iPad "自由笔记" (FreeNotes), organized by course.
双语学习笔记归档：iPad「自由笔记」导出的 PDF，按课程整理。

---

## 1. Purpose / 用途

| English | 中文 |
|---------|------|
| Archive lecture notes and homework as PDFs. | 归档课堂笔记与课后习题（PDF）。 |
| Filenames use English terminology first, then Chinese, so the repository doubles as a technical-English drill. | 文件名以英文术语在前、中文在后，使仓库同时可用于训练专业英语。 |
| One topic per file keeps files small and searchable. | 一个主题一个文件，体积小、便于检索。 |

---

## 2. Directory Structure / 目录结构

Directories are **pure English** (no Chinese, no spaces) so paths stay shell-friendly.
目录名为**纯英文**（无中文、无空格），便于命令行操作。

```
notes/
├── 01-College-Physics/                      大学物理
│   ├── 01-Lecture-Notes/                    课堂笔记
│   └── 02-EX/                               课后习题
├── 02-Analog-Electronics/                   模拟电子技术基础
│   ├── 01-Lecture-Notes/
│   └── 02-EX/
├── 03-Digital-Electronics/                  数字电子技术基础
│   ├── 01-Lecture-Notes/
│   └── 02-EX/
├── 04-Signals-and-Systems/                  信号与系统
│   ├── 01-Lecture-Notes/
│   │   └── Chapter-01-Signals-and-Systems-Basics-信号与系统基本概念/
│   └── 02-EX/
├── 05-Complex-Analysis-and-Integral-Transforms/   复变函数与积分变换
│   ├── 01-Lecture-Notes/
│   └── 02-EX/
├── 06-Advanced-Mathematics/                 高等数学
│   ├── 01-Lecture-Notes/
│   └── 02-EX/
└── _Inbox/                                  待归档（临时中转）
```

The leading numbers pin the sort order on GitHub; `Lecture-Notes` always sorts before `EX`.
序号前缀固定 GitHub 上的排序；`Lecture-Notes` 永远排在 `EX` 前面。

Where notes are written episode by episode (currently **04 Signals and Systems**), a `Chapter-NN-...` folder groups the episodes of one chapter; the PDFs sit directly inside it.
逐集记录笔记的课程（目前为 **04 信号与系统**）额外用 `Chapter-NN-...` 文件夹把同一章的集数归拢，PDF 直接放在该文件夹内。

---

## 3. Naming Convention / 命名规范

```
NN-English-Terminology-中文术语.pdf
```

| Rule | 规则 |
|------|------|
| `NN` = two-digit chapter number starting at `01`; cover pages use `00`. | `NN` 为两位章号，从 `01` 起；封面统一为 `00`。 |
| English part uses TitleCase with hyphens, no spaces. | 英文部分用连字符连接的 TitleCase，不含空格。 |
| Chinese part mirrors the English meaning. | 中文部分与英文含义对应。 |
| Multiple topics joined with hyphens in both parts. | 一章多个主题时，中英文部分都用连字符连接。 |
| **Lecture notes: one page = one PDF.** | **笔记：一页 = 一个 PDF。** |
| **EX (exercises): one chapter = one PDF.** | **习题：一章 = 一个 PDF。** |
| Inside an episode-based course, `NN` counts episodes within that chapter folder. | 逐集记录的课程中，`NN` 表示该章文件夹内的集号。 |

Examples / 示例:

- `01-Kinematics-of-a-Particle-质点运动学.pdf`
- `12-Electrostatic-Field-Potential-and-Potential-Energy-静电场-电势与电势能.pdf`
- `01-Chapter-3-Assignment-第3章作业.pdf`
- `Chapter-01-Signals-and-Systems-Basics-信号与系统基本概念/03-Typical-Systems-典型的系统.pdf`

---

## 4. Index / 索引

### 01 College Physics · Lecture Notes / 大学物理 · 笔记

| No. | English | 中文 |
|-----|---------|------|
| 00 | Cover | 封面 |
| 01 | Kinematics of a Particle | 质点运动学 |
| 02 | Angular and Linear Quantities; Newton's Laws | 角量与线量关系、牛顿三定律 |
| 03 | Momentum, Impulse and Conservation | 动量、冲量与动量守恒 |
| 04 | Work, Kinetic Energy and Mechanical Energy Conservation | 功、动能定理与机械能守恒 |
| 05 | Moment of Inertia | 刚体转动惯量 |
| 06 | Torque and Rotation Theorem | 力矩与转动定理 |
| 07 | Angular Momentum and Its Conservation | 角动量与角动量守恒 |
| 08 | Work and Energy in Rigid-Body Rotation | 刚体转动的功与能 |
| 09 | Kinetic Theory of Gases | 气体动理论 |
| 10 | Electrostatic Field — Field Intensity | 静电场 — 电场强度 |
| 11 | Electrostatic Field — Gauss's Law | 静电场 — 高斯定理 |
| 12 | Electrostatic Field — Potential and Potential Energy | 静电场 — 电势与电势能 |
| 13 | Electrostatic Field — Conductors and Capacitance | 静电场 — 导体与电容 |
| 14 | Electrostatic Field — Dielectrics and Field Energy | 静电场 — 电介质与电场能 |
| 15 | Steady Magnetic Field — Biot–Savart Law and Ampère's Circuital Law | 稳恒磁场 — 毕奥-萨伐尔定律、安培环路定理 |
| 16 | Steady Magnetic Field — Magnetic Flux and Gauss's Law | 稳恒磁场 — 磁通量与高斯定理 |
| 17 | Ampère Force, Magnetic Moment and Lorentz Force | 安培力、磁矩与洛伦兹力 |

### 01 College Physics · EX (Exercises) / 大学物理 · 课后习题

| No. | English | 中文 | Problems / 题号 |
|-----|---------|------|-----------------|
| 00 | Cover | 封面 | — |
| 01 | Kinematics of a Particle — Problems | 质点运动学习题 | 1-1 ~ 1-45 |
| 02 | Momentum and Energy — Problems | 动量与能量习题 | 2-2 ~ 2-54 |
| 03 | Rigid-Body Rotation — Problems | 刚体转动习题 | 3-3 ~ 3-24 |
| 04 | Kinetic Theory of Gases — Problems | 气体动理论习题 | 5-3 ~ 5-16 |
| 05 | Electrostatic Field — Problems | 静电场习题 | 7-40 ~ 7-52 |
| 06 | Final Review Questions A1/B | 期末复习思考题 A1/B | Q&A, MC, fill-in, calculation |

### 02 Analog Electronics · Lecture Notes / 模拟电子技术基础 · 笔记

| No. | English | 中文 |
|-----|---------|------|
| 00 | Cover | 封面 |
| 01 | Common Semiconductor Devices | 常用半导体器件 |
| 02 | PN-Junction Characteristics | PN 结特性 |
| 03 | Semiconductor Diodes | 半导体二极管 |
| 04 | Diode Circuit Analysis | 二极管电路分析 |
| 05 | Zener Diodes | 稳压二极管 |
| 06 | Bipolar Junction Transistors | 三极管 |

### 02 Analog Electronics · EX (Exercises) / 模拟电子技术基础 · 课后习题

| No. | English | 中文 | Problems / 题号 |
|-----|---------|------|-----------------|
| 01 | Chapter 3 Assignment | 第 3 章作业 | 3.4, 3.5, 3.9, 3.10, 3.13 |

### 05 Complex Analysis and Integral Transforms · Lecture Notes / 复变函数与积分变换 · 笔记

| No. | English | 中文 |
|-----|---------|------|
| 00 | Cover | 封面 |
| 01 | Complex Numbers | 复数 |
| 02 | Analytic and Harmonic Functions | 解析函数与调和函数 |
| 03 | Elementary Complex Functions | 初等复变函数 |
| 04 | Integration of Complex Functions | 复变函数的积分 |
| 05 | Power Series and Taylor Series | 幂级数与泰勒级数 |
| 06 | Laurent Series and Isolated Singularities | 洛朗级数与孤立奇点 |
| 07 | Residues and the Residue Theorem | 留数与留数定理 |
| 08 | Evaluating Definite Integrals by Residues | 用留数计算定积分 |

### 04 Signals and Systems · Lecture Notes / 信号与系统 · 笔记

Notes follow the Bilibili course episode by episode, grouped into chapter folders.
笔记按 B 站课程逐集命名，归入章节目录。

`01-Lecture-Notes/00-Cover-封面.pdf`, then `Chapter-01-Signals-and-Systems-Basics-信号与系统基本概念/`:

| No. | English | 中文 |
|-----|---------|------|
| 01 | Typical Signals | 典型的信号 |
| 02 | Transformations of the Independent Variable | 信号的自变量变换 |
| 03 | Typical Systems | 典型的系统 |
| 04 | Typical Systems (Part 2) | 典型的系统（下） |
| 05 | Definition of LTI Systems | LTI 系统的定义 |

### 06 Advanced Mathematics · Lecture Notes / 高等数学 · 笔记

| No. | English | 中文 | Scope / 范围 |
|-----|---------|------|--------------|
| 01 | Advanced Mathematics II — Framework | 高数下知识框架 | Mind-map canvas covering multivariable differentiation, multiple/line/surface integrals and infinite series / 思维导图：多元微分、重积分、曲线曲面积分、无穷级数 |

> This file is a single large canvas (5844 × 5510 pt, 136 embedded images, effective 143–275 DPI). It is stored **byte-for-byte as exported** — no re-encoding, no downsampling — so it stays readable at any zoom. At 23.9 MB it is well under GitHub's 100 MB per-file limit.
> 该文件是一张大型画布（5844 × 5510 pt，内嵌 136 张图，有效分辨率 143–275 DPI）。**按导出原样逐字节保存**，未做任何重编码或降采样，保证任意缩放都清晰可读。23.9 MB 远低于 GitHub 单文件 100 MB 上限。

### 03 Digital Electronics · Lecture Notes / 数字电子技术基础 · 笔记

| No. | English | 中文 |
|-----|---------|------|
| 00 | Cover | 封面 |
| 01 | Formula Simplification Method | 公式化简法 |

### 03 Digital Electronics · EX (Exercises) / 数字电子技术基础 · 课后习题

| No. | English | 中文 |
|-----|---------|------|
| — | Awaiting material | 待上传 |

---

## 5. Technical Notes / 技术说明

| English | 中文 |
|---------|------|
| Handwritten ink in FreeNotes exports is **vector**, so it stays sharp at any zoom. | 自由笔记导出的手写笔迹是**矢量**，任意缩放都清晰。 |
| PDF size comes mostly from embedded raster screenshots; recompressing those at JPEG q=88 with an 1800 px cap cuts size ~60–80% with no visible loss to handwriting. | PDF 体积主要来自内嵌的栅格截图；以 JPEG q=88、1800px 上限重压可减小约 60–80%，手写部分无可察觉损失。 |
| **Exception — large canvas exports** (e.g. mind maps): stored **as exported**, with no re-encoding and no downsampling. These files are meant to be zoomed, so every original pixel is kept; they are well under the 100 MB limit anyway. | **例外 —— 大型画布导出**（如思维导图）：**按导出原样保存**，不做重编码、不降采样。这类文件的用途就是自由缩放，因此保留全部原始像素；其体积本来也远低于 100 MB 上限。 |
| GitHub warns above 50 MB and rejects files above 100 MB per file. | GitHub 单文件超过 50 MB 会告警，超过 100 MB 直接拒绝。 |
| Keep total repo size under ~1 GB before considering Git LFS. | 仓库总量超过约 1 GB 再考虑 Git LFS。 |
| EX PDFs containing a handwritten name or student ID are redacted before upload. | 含手写姓名或学号的习题 PDF，上传前会先做遮罩处理。 |
| `_Inbox/` is a staging area — move files into the right course promptly. | `_Inbox/` 是临时中转区 — 请及时把文件归入对应课程。 |
