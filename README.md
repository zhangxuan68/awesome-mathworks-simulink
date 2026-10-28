# Awesome MathWorks Simulink Models

MathWorks 官方在 GitHub 上开源的 **MATLAB / Simulink / Simscape 工程模型**汇总,聚焦汽车、机器人与自动驾驶方向。

本清单内所有仓库链接均经过 `git ls-remote` 验证可访问。

---

## 目录

- [组织入口](#组织入口)
- [整车与动力总成](#整车与动力总成)
- [自动驾驶与地面机器人](#自动驾驶与地面机器人)
- [机械臂与足式机器人](#机械臂与足式机器人)
- [工程机械与其他载具](#工程机械与其他载具)
- [电力电子](#电力电子)
- [官方清单与示例入口](#官方清单与示例入口)
- [重要说明](#重要说明)

---

## 组织入口

| 组织 | 方向 | 链接 |
|---|---|---|
| **mathworks** | MathWorks 主账号,涵盖各行业示例 | https://github.com/mathworks |
| **simscape** | Simscape 物理建模专项(29 个仓库) | https://github.com/simscape |
| **mathworks-robotics** | 机器人与自动驾驶团队 | https://github.com/mathworks-robotics |

---

## 整车与动力总成

| 项目 | 说明 |
|---|---|
| [vehicle-modeling](https://github.com/mathworks/vehicle-modeling) | 三套整车模型:车辆动力学 glider、纯电动车(BEV)、传统燃油车。分 Simulink 与 Powertrain Blockset 两种实现,演示用功率损失法建模各部件 |
| [Simscape-Vehicle-Templates](https://github.com/mathworks/Simscape-Vehicle-Templates) | Simscape 整车模板库,可配置悬架、转向、动力总成等 |
| [Simscape-Battery-Electric-Vehicle-Model](https://github.com/mathworks/Simscape-Battery-Electric-Vehicle-Model) | Simscape 纯电动车模型 |
| [Simscape-Hybrid-Electric-Vehicle-Model](https://github.com/mathworks/Simscape-Hybrid-Electric-Vehicle-Model) | Simscape 混合动力车模型 |
| [Electric-Vehicle-Simscape](https://github.com/simscape/Electric-Vehicle-Simscape) | 纯电动车建模,用于续航估算与电池选型 |
| [Optimize-BEV-Thermal-Management-with-Simscape](https://github.com/simscape/Optimize-BEV-Thermal-Management-with-Simscape) | 带热管理的纯电动车模型,面向热管理系统优化 |
| [Optimize-Vehicle-Design-with-AI-and-Simscape](https://github.com/simscape/Optimize-Vehicle-Design-with-AI-and-Simscape) | 从多体车辆动力学模型构建 AI 代理模型(surrogate model)做设计优化 |
| [Formula-Student-Vehicle-Simscape](https://github.com/simscape/Formula-Student-Vehicle-Simscape) | 方程式赛车模板,含多体悬架与电动动力总成 |

---

## 自动驾驶与地面机器人

| 项目 | 说明 |
|---|---|
| [autonomous-navigation-ugv](https://github.com/mathworks-robotics/autonomous-navigation-ugv) | 移动机器人与无人地面车辆的导航栈开发 |
| [Offroad-Navigation-for-Autonomous-Haul-Trucks](https://github.com/mathworks-robotics/Offroad-Navigation-for-Autonomous-Haul-Trucks) | 自动驾驶矿用卡车的越野导航 |
| [Tractor-Sprayer-Navigation-in-Vineyard](https://github.com/mathworks-robotics/Tractor-Sprayer-Navigation-in-Vineyard) | 葡萄园喷雾拖拉机导航,基于 Unreal Engine 场景 |
| [mobile-robotics-simulation-toolbox](https://github.com/mathworks-robotics/mobile-robotics-simulation-toolbox) | 移动机器人仿真工具箱 |
| [robotics-playground](https://github.com/mathworks-robotics/robotics-playground) | 机器人教学用虚拟场景 |
| [deep-learning-for-3D-object-detection](https://github.com/mathworks-robotics/deep-learning-for-3D-object-detection) | 点云三维目标检测 |

---

## 机械臂与足式机器人

| 项目 | 说明 |
|---|---|
| [designing-robot-manipulator-algorithms](https://github.com/mathworks-robotics/designing-robot-manipulator-algorithms) | 机械臂运动学与逆运动学算法设计 |
| [trajectory-planning-robot-manipulators](https://github.com/mathworks-robotics/trajectory-planning-robot-manipulators) | 机械臂轨迹规划 |
| [msra-walking-robot](https://github.com/mathworks-robotics/msra-walking-robot) | 步行机器人建模与仿真 |
| [Cartesian-Robot-Design-Simscape](https://github.com/simscape/Cartesian-Robot-Design-Simscape) | 参数化笛卡尔机器人系统级模型,用于加速 CAD 设计迭代 |

---

## 工程机械与其他载具

| 项目 | 说明 |
|---|---|
| [Excavator-Simscape](https://github.com/simscape/Excavator-Simscape) | 挖掘机设计:铰点布置、挖掘力与倾翻指标、载荷图、挖掘循环仿真 |
| [Wheel-Loader-Simscape](https://github.com/simscape/Wheel-Loader-Simscape) | 轮式装载机设计:CVT 选型、不平地面行驶、举升与卸料循环 |
| [Mining-Loader-Simscape](https://github.com/simscape/Mining-Loader-Simscape) | 矿用装载机执行系统载荷循环测试与制动距离估算 |
| [eVTOL-Drone-Simscape](https://github.com/simscape/eVTOL-Drone-Simscape) | eVTOL 电动垂直起降无人机动力总成,含续航、电池选型与控制调参 |
| [modeling-and-simulation-of-an-AUV-in-Simulink](https://github.com/mathworks-robotics/modeling-and-simulation-of-an-AUV-in-Simulink) | 自主水下航行器建模与仿真 |
| [AUV-modeling-and-sim](https://github.com/mathworks/AUV-modeling-and-sim) | AUV 动力学与控制 |

---

## 电力电子

| 项目 | 说明 |
|---|---|
| [Modeling-Power-Electronics-Systems-in-Simscape](https://github.com/simscape/Modeling-Power-Electronics-Systems-in-Simscape) | 电流控制型电力电子建模,涵盖求解器设置、PWM 生成与 ADC 建模 |
| [Power-Converter-Circuit-Control-Simscape](https://github.com/simscape/Power-Converter-Circuit-Control-Simscape) | 功率变换器电路设计与控制策略 |

---

## 官方清单与示例入口

- [awesome-matlab-robotics](https://github.com/mathworks-robotics/awesome-matlab-robotics) — MathWorks 官方维护的机器人方向资源清单(注:内容停更于 2020 年,以文档链接为主)
- [Automated Driving Toolbox 示例](https://www.mathworks.com/help/driving/examples.html) — 车道保持、传感器融合、激光雷达跟踪、自动泊车等
- [Simscape 示例](https://www.mathworks.com/help/physmod/simscape/examples.html)
- [Control System Toolbox 示例](https://www.mathworks.com/help/control/examples.html)
- [Reinforcement Learning Toolbox 示例](https://www.mathworks.com/help/reinforcement-learning/examples.html)
- [Sensor Fusion and Tracking Toolbox 示例](https://www.mathworks.com/help/fusion/examples.html)

---

## 重要说明

**1. GitHub 不是 MathWorks 模型的主要发布渠道。** 相当多官方模型只发在 [MATLAB Central File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/),不在 GitHub 上。找特定模型时 File Exchange 往往比 GitHub 更全,例如:

- [Simscape Vehicle Templates](https://www.mathworks.com/matlabcentral/fileexchange/79484-simscape-vehicle-templates)
- [Battery Electric Vehicle Model in Simscape](https://www.mathworks.com/matlabcentral/fileexchange/82250-battery-electric-vehicle-model-in-simscape)
- [Electric Vehicle Design with Simscape](https://www.mathworks.com/matlabcentral/fileexchange/124795-electric-vehicle-design-with-simscape)

**2. 运行这些模型需要对应的商业许可。** 多数依赖 Simulink、Simscape、Powertrain Blockset、Automated Driving Toolbox 等付费工具箱,仓库本身开源不等于可以免费运行。打开前先看 README 里的 Required Products。

**3. 清单覆盖度。** `simscape` 组织共 29 个仓库,其页面仅公开展示 15 个,本清单收录了其中与汽车、机器人相关的部分。未展示的 14 个未能核实,可能还有遗漏,建议直接浏览组织主页。

**4. 不含第三方项目。** 本清单只收 MathWorks 官方账号(`mathworks`、`simscape`、`mathworks-robotics`)下的仓库。GitHub 上有大量个人或高校发布的 MATLAB/Simulink 汽车项目,质量参差,不在此列。
