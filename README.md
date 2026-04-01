# Lumi 路明｜Open Collaborative Guide Robot Demo

> If AI can have warmth, I hope it first warms the roads that some people cannot see.

Lumi 路明是一个面向**视障出行场景**的开放共创导盲机器人 Demo 项目。

当前阶段，我们**不是以商业化为第一目标**。  
我们希望先完成一个真正可运行、可演示、可验证的 Demo，去回答一个很具体的问题：

**能不能用更低成本、更开放的方式，做出一个真正有公益价值的导盲机器人硬件原型？**

---

## Project Background

视障出行，至今仍然是一个真实存在、但长期被低估的问题。

传统盲杖成本低、普及广，但感知范围有限，难以应对台阶、动态障碍和复杂陌生路线。  
专业导盲犬体验优秀，但培养成本高、供给极少，难以规模化。  
Lumi 想探索的是第三种可能：

**让手机负责“看与算”，让硬件负责“走与停”，以开放共创的方式做出一套更可及的辅助出行方案。**

---

## Current Goals

本项目当前聚焦于 **Demo 验证阶段**。

现阶段目标非常明确：

- 完成硬件原型
- 完成基础运动控制
- 完成手机通信
- 完成最低限度安全制动
- 完成可演示场景验证

这意味着，Lumi 现在不是完整商业产品，也不是量产项目。  
它首先是一个认真推进的 **开放共创 Demo**。

---

## Current Direction

Lumi 当前的核心思路是：

- **手机负责看与算**
  - 视觉感知
  - 语音交互
  - 地图与导航

- **硬件负责走与停**
  - 运动执行
  - 转向控制
  - 紧急制动
  - 失联保护

- **安全兜底优先于智能能力**
  - 即使算法不完善，底层硬件也应具备最基本的安全托底能力

项目整体是一个“软硬解耦”的方向：  
上层 App、算法、视觉能力可以持续演进；  
下层硬件则优先做好稳定执行与安全边界。

---

## We Are Looking For

We are looking for early collaborators.

### 1) 电子 / 嵌入式工程师
方向包括但不限于：

- 电机驱动
- 电池 / BMS
- 主控板
- 蓝牙 / Wi-Fi 通信
- 急停 / 保护机制
- 基础固件接口

### 2) 结构 / 机械工程师
方向包括但不限于：

- 杖体结构设计
- 双轮 / 底盘集成
- 手机支架方案
- 防跌落 / 重心设计
- 可装配性与可靠性打样

### 3) 控制 / 机器人运动工程师
方向包括但不限于：

- 差速控制
- 转向逻辑
- 刹停逻辑
- 基础状态机
- 低速跟随与稳定性调参

### 4) 视频制作 / 内容传播伙伴
希望你能帮助我们：

- 记录共创过程
- 剪辑阶段性内容
- 协助传播与基础运营
- 让更多人知道这件公益项目正在发生

### 5) 器件 / 资源赞助伙伴
当前欢迎支持的方向包括：

- BLDC 电机 / 减速器
- 电机驱动板
- MCU / 开发板
- IMU / ToF / 超声波模块
- 电池与充电模组
- 电磁制动器
- 铝合金结构件 / CNC / 3D 打印
- 手机支架 / 连接器 / 线束
- 小批量 PCBA 打样
- 地图 API / 云服务 credits

---

## Collaboration Model

为了让项目更清晰地推进，  
Lumi 当前采用 **开放共创、角色分层、边界清晰** 的合作方式。

**不是所有参与者都会被定义为“合伙人”或“联合创始人”。**

当前合作关系主要分为 4 类：

### 核心共创成员
- 长周期参与
- 每周稳定投入
- 对具体模块结果负责

### 顾问 / 导师
- 提供技术、方向或资源建议
- 不负责具体交付

### 供应链 / 器件支持伙伴
- 提供器件、样机、加工、打样等资源
- 不深度参与日常研发节奏

### 公益 / 场景验证伙伴
- 包括盲协、公益组织、志愿者、测试支持方等
- 帮助做真实场景验证和体验反馈

---

## What You Can Expect

如果你加入这个项目，你可以期待的，不只是“帮个忙”，而是：

### 1. 一次真实的 0-1 项目经验
从产品定义、硬件打样、控制验证、结构优化，到协作推进和公开展示，这会是一次真正从想法走向 Demo 的实践过程。

### 2. 一件有公益价值、也有趣的事
如果能用机器人和 AI，为视障出行这个问题做出一点点真正有意义的尝试，这本身就是一件很酷的事。

### 3. 未来继续参与的可能性
当前阶段是开放共创。  
如果未来项目逐步成熟，进入更正式的组织化、公司化或商业化阶段，早期深度参与者将拥有优先继续参与的机会。

---

## Current Priorities

当前优先级最高的事情包括：

- 搭建第一版 Demo 硬件架构
- 明确底盘 / 杖体 / 手机支架基础方案
- 跑通基础通信链路
- 建立最低限度安全制动逻辑
- 完成首轮可演示场景验证
- 吸引第一批认同项目的共创伙伴

---

## Safety First

这是一个涉及真实出行场景的辅助科技方向项目。  
因此在 Demo 阶段，我们始终坚持：

- 安全边界优先
- Demo 不等于正式产品
- 所有验证应在清晰、可控、谨慎的条件下进行
- 任何智能能力都不能替代必要的人工监护与接管

---

## Roadmap

### Phase 0
Project setup
- README
- collaboration rules
- recruitment
- early discussions
- first technical alignment

### Phase 1
Demo prototype
- hardware prototype
- basic motion control
- phone communication
- minimal braking logic
- demo scenario validation

### Phase 2
Structured iteration
- reliability improvements
- modular architecture
- sensor enhancement
- better control stability
- better field validation process

### Phase 3
Future possibilities
- broader collaboration
- more complete open interface
- scenario partnerships
- potential formalization / company setup / long-term product path

---

## Contact

项目发起人：司马

- Email: szemasiu@gmail.com
- WeChat: nicksima

如果你愿意一起参与，欢迎联系。  
如果你身边有合适的工程师、传播伙伴、公益组织、供应链朋友，也欢迎转给他们。

---

## Final Note

很多有价值的事，  
不是等条件完美了才开始，  
而是先有一群人愿意认真把第一步做出来。

Lumi 路明，希望先把第一步做出来。  
一起共创，一起把这条路点亮一点。
