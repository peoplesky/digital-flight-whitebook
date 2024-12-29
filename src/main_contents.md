# 第三章：数字飞行的主要内容

以下是数字飞行的定义，这是本文描述的基础：

> **数字飞行** 是一种操作模式，其中飞行操作是通过参考数字信息进行的，操作员通过连接的数字技术和自动化信息交换，采用合作实践和自我隔离来确保飞行路径安全。

选择术语“数字”来表示通过参考数字元素（即信息、连接性和计算自动化）进行飞行操作。命名与视觉飞行（编纂为 VFR，通过视觉参考进行飞行操作）和仪表飞行（编纂为 IFR，通过参考仪表进行飞行操作）平行。建议将数字飞行正式以法规形式制定为新的操作模式，并编纂为新的飞行规则，此处称为数字飞行规则（DFR）。

> **数字飞行规则** 是一组授权持续数字飞行的法规，作为在 VMC 和 IMC 中进行隔离的替代方式，以代替采用视觉程序（即 VFR）或接收 ATC 分隔服务（即 IFR）。

在 DFR 颁布之前，设想某些数字飞行能力将在咨询或辅助基础上获得 VFR 或 IFR 下的使用授权。这将建立通往全面 DFR 的增量路径，同时提供早期和持续的运营效益。即使在全面实施 DFR 之后，某些数字飞行能力预计也会有益于选择在 VFR 和 IFR 下运营的空域用户。

在本文中，术语“数字飞行”用于包含拟议的 DFR 监管操作模式下的功能，以及在 VFR 或 IFR 下的任何点补充使用的数字飞行能力。缩写 DFR 用于上下文为正式建立的飞行规则的情况。目的是强调操作模式，而不是将授权的特定法规。如果最终采用数字飞行或类似概念，监管机构将确定其授权的形式和命名。

## 3.1. ICAO 基础

这项新的操作模式建议有意与国际民航组织全球空中交通管理 (ATM) 运营概念（第一版）[20] 相一致。数字飞行符合该概念的安全、人类、技术、信息、协作和连续性的指导原则。这些原则强调安全是最高优先级，认识到人类在管理运营中的基本作用，并侧重于功能需求而不是特定技术。它们还强调了质量保证信息共享对于实现动态和灵活的决策制定以及突发事件管理对于确保服务连续性的重要性。此外，[4] 中提出并在此处应用的一套定义新飞行规则的指导原则是，新飞行规则应保留并区别于 VFR 和 IFR；应正式确立运营商的分隔责任；应增加空域访问和灵活性；应提供给所有满足要求的运营商；不应要求与 VFR 和 IFR 操作隔离；应具有可扩展性和抗干扰能力；并且应能够逐步引入。

国际民航组织全球 ATM 运营概念提供了一种结构，通过该结构可以将数字飞行建立为一种独特的操作模式，其定义是通过其冲突管理方法。国际民航组织结构由三层冲突管理组成：

1.  战略冲突管理是冲突管理的第一层，通过空域组织和管理、需求和容量平衡以及交通同步组件来实现。
2.  隔离提供是冲突管理的第二层，是使飞机与危险保持至少适当隔离最小值战术过程。
3.  防撞是冲突管理的第三层，必须在隔离模式受到破坏时激活。

虽然数字飞行与所有三个层次相关联，但它主要通过其实现第二层隔离提供的方式与其他操作模式区分开来。国际民航组织概念将隔离者定义为“负责冲突隔离提供的代理，可以是空域用户或隔离提供服务提供商”。根据国际民航组织的概念，为避免歧义，必须预先为所有危险定义预定的隔离者，尽管该角色可能因不同的危险而分配给不同的代理（例如，空域用户应对天气负责，服务提供商应对交通负责）。虽然隔离者的角色可以被委托，但预定的隔离者是委托结束后责任返回的代理人 [20]。

国际民航组织概念指出，“预定的隔离者将是空域用户，除非安全或 ATM 系统设计需要隔离提供服务。”与此声明一致的是，DFR 被定义为一种操作模式，其中空域用户是预定的隔离者，通过确保以与 ATM 系统设计兼容的方式实现安全的方式（即数字元素）来完成此角色。具体而言，数字飞行将飞机运营商确立为隔离提供的责任方，并应用自动化作为隔离者的负责工具。因此，DFR 运营商将“交通隔离者”的角色委托给经过交通隔离功能认证的自动化，而运营商仍然负责自动化的正确安装、维护和使用。飞行员作为运营商的代理人，可以与自动化进行交互，但运营商仍然负责。因此，DFR 运营商现在负责所有危险隔离，包括交通隔离（区分 DFR 和 IFR，其中交通隔离由 ATC 提供）。此外，DFR 运营商必须应用适当的量化隔离最小值，即飞机与危险之间允许的最小位移（区分 DFR 与 VFR，VFR 规定了 “保持安全距离”的未量化主观要求）。

数字飞行也可以从冲突管理的第一层和第三层角度来看待。根据国际民航组织概念，战略冲突管理层的目标是“将应用第二层隔离提供——降至由 ATM 系统设计和运营确定的适当级别。”在 IFR 的背景下，隔离提供主要以人为中心并且偶尔会成为工作量密集型任务，因此 IFR 的战略冲突管理旨在减少控制员的工作量，以确保可以在其限制范围内轻松提供隔离服务。然而，在 DFR 的背景下，隔离提供是自动化的，因此不会像以人为中心的方法那样存在相同的限制。战略冲突管理仍将用于 DFR，但不会用于管理隔离提供中控制员工作量的那些方面。例如，它将包括与确保有效使用与 IFR 航班共享的容量有限的物理资源相关的交通同步要素，DFR 运营商可以通过其贡献有价值的功能来增强效率。DFR 运营商还将以各种方式贡献其自身的战略冲突管理，以确保自我隔离功能在交通密度或复杂性增加时，以可接受的风险水平执行。

数字飞行的防撞层将类似于今天的机载防撞能力，其应用程序更统一，并且解决方案可能由自动化而不是作为飞行员执行的建议来颁布。它可能会采用新的防撞技术，这些技术除了垂直维度外，还使用横向和速度机动维度。

## 3.2. 主要优势

作为一种新的操作模式，数字飞行提供了特定的运营商利益，这些利益与新的运营商责任相一致。不同类型的运营商（例如，私人运营商、商业运营商、航空公司）和新进入的运营概念（例如，UAM、ETM、区域空中交通）将能够以创新和潜在多样的方式部署这些利益以获得特定的价值（在第 4 部分价值主张中进一步讨论）。数字飞行提出的主要运营优势是：

*   **空域访问**——无需外部视觉参考（即所有天气条件）且无需特定 ATC 许可即可在所有空域等级（即 A、B、C 和 D 类空域）中运行的能力。
*   **运营灵活性**——无需外部视觉参考且无需特定 ATC 许可即可动态更改飞行路径意图的能力。

“外部视觉参考”是指 VFR 的飞行能见度和云层间隙要求。与 IFR 运营商一样，DFR 运营商不受这些要求的约束，因此可以在 VMC 和 IMC 下平等地运行。“特定 ATC 许可”是指 ATC 给予特定航班执行特定操作的授权。与 VFR 运营商一样，DFR 运营商不依赖 ATC 分隔服务，因此在大多数情况下不需要特定许可。（第 3.4 节适用环境中介绍了例外情况。）

这两个对 DFR 运营商的主要好处（在第 4.3.1 节“价值主张：运营商”中进一步描述）是通过运营商负责应用合作实践进行自我隔离来实现的。在第 3.5 节“基本要素”中详细介绍，合作实践是一组预期、补充、运营行为，可促进空域及其资源的有效和公平共享。这些实践被编码到隔离自动化中，以确保它们被可靠和一致地应用。预期结果是数字飞行被所有人都认可并接受为安全、合作和基于性能的空域运营方式。

## 3.3. 运营整合

DFR 操作旨在与 VFR 和 IFR 操作共享空域，而无需新的空域等级或隔离空域。几种机制将实现与现有操作模式的协调运营整合，同时仍能适应未来的技术进步。

*   **运营兼容性：**即使在 DFR 被正式确立为一套新的飞行规则之前，数字飞行能力也将被引入并开始在 VFR 和 IFR 下使用（具有豁免、偏差、放弃或许可（如适用 [21]）），从而从一开始就开发与这些操作模式的兼容性。兼容性意味着 VFR 和 IFR 交通信息被纳入 DFR 技术和程序，以使 DFR 操作不会抑制或中断非 DFR 操作。鉴于这种兼容性，向 DFR 的监管过渡在很大程度上应该对 VFR 和 IFR 运营商是透明的，他们将继续拥有他们今天所拥有的相同级别的空域访问和运营灵活性。这种透明过渡的关键是 DFR 合作实践“尊重”这些非 DFR 操作，这意味着积极管理其存在中的冲突，并确保不会给执行这些操作的飞行员和管制员增加新的负担。为了确保兼容集成，更广泛的社区将协作开发进一步的要求，以确保实现各种操作模式之间的理想公平性。

*   **可预测行为：**与现有操作模式相比，DFR 操作将表现出高度合作和可预测的行为，本质上确保 DFR 操作被视为“好邻居”。编码在隔离自动化中的合作实践应该产生预期和可预测的行动，这些行动被视为对共享空域的人们是友好的。虽然 DFR 操作保持灵活（即，可以随意更改飞行路径意图），但它们的可预测行为在于主动共享意图，并且更改以与既定规则兼容的方式进行（例如，提供提前通知，不造成新的冲突）。

*   **可靠的性能：**数字飞行将作为基于性能的运营模式进行开发。因此，它不仅会为 DFR 运营商带来运营利益，还会为空域系统带来运营利益。例如，高性能的 DFR 运营商将能够应用可根据各个遭遇情况量身定制的分隔标准，考虑到交通的飞行规则、共享意图和所涉及飞机的性能等因素。精确的分隔标准提高了空域访问和飞行效率，从而提高了整体空域容量。作为一种基于性能的操作模式，数字飞行将允许整合不断进步的技术，添加新功能和改进的功能。数字飞行不会是一种静态能力，而是将成为技术进步能够实现新的数字飞行能力的长期创新的基础。

## 3.4. 适用环境

DFR 操作旨在允许在所有空域等级中使用。如所指定的，它不需要隔离的空域或需要创建新的空域等级。虽然 DFR 操作最终将在每个空域等级中进行，如图 1 所示，但它们可能会首先在某些等级和特定类型的操作中引入，然后在后期扩展到那些风险承受能力较低的等级。

**3.4.1. 空域进入**

目前在法规中定义的空域等级进入和双向通信要求将被修改，以便以一种最大限度地减少 ATC 负担的方式来适应 DFR 操作。即使 ATC 不向 DFR 飞机提供隔离服务，某些情况（如 VFR 的情况）也可能需要 DFR 飞机在 ATC 许可下运行。引入了当前发出的许可（即特定许可、当前实践）和监管批准（拟议添加）之间的区别：

*   **特定许可**——特定许可由空中交通管制员在运营时按呼号发给特定航班，就像今天的管制员一样。此类许可可以通过语音或数据通信发出。可能需要 DFR 飞机的特定许可的情况包括在 B、C 和 D 类空域内的塔台机场滑行、起飞和着陆的许可。在这里，ATC 正在管理进出港的流量，无论航班以哪种飞行规则进行。同样，受益于 ATC 到达排序的 DFR 飞机应期望在许可下运行并像任何其他到达一样对待。然而，DFR 与交通流量管理 (TFM) 自动化协作的能力将允许在无需 ATC 矢量和速度控制的情况下合并到交通流量中。同样，可以利用 DFR 的精确间隔能力来提高跑道吞吐量。起飞后，DFR 飞机可以期望被“允许进行 DFR”，这意味着运营商应该从那时起开始行使自我隔离的责任。

*   **监管批准**——监管批准使飞机能够在满足进入监管要求的基础上进入受控空域，但不需要航线和高度许可。例如，目前仅为 IFR 航班保留的 A 类空域，因此将根据 DFR 航班进入空域而无需特定许可的监管批准，包括 IFR 和 DFR 航班。虽然在受控空域内，在 DFR 下编纂的合作实践将要求 DFR 飞机在与 IFR 飞机发生冲突之前解决所有冲突。

图 1 - 空域等级进入要求因操作模式而异。FAA 上方表格的图形。

在管制员的决策时间范围内引入许可，从而最大限度地减少 ATC-IFR 操作的中断。B 类空域目前可容纳 VFR 和 IFR 飞机，并且两者都受正向控制，现在还将容纳 DFR 航班，在主机场着陆时也受正向控制。但是，允许 DFR 飞机在 B 类空域中转（即，不在 ATC 控制机场着陆）时无需特定许可，而只需监管批准。合作实践将再次要求 DFR 飞机避开主要的进出港流量，可能通过地理围栏来避免中断。所有飞机将通过语音或数据通信与 ATC（包括 DFR）进行通信，并且能够在需要时遵循 ATC 指令。但是，促进空域集成的 DFR 的合作行为将最大限度地减少对 ATC 指令的需求。

*   **无需许可**——不希望需要 DFR 飞机许可的情况是在 C、D、E 和 G¹ 类空域（尽管在 C 类和 D 类机场仍需要着陆许可）中进入和运行。这些空域等级目前不需要进入许可。允许 DFR 飞机在 IMC 和 VMC 中无需许可运行。

*   **双向通信**——空域进入的一个重要要求（对于 A、B、C 和 D 类）是在进入之前与 ATC 建立双向通信。DFR 飞机始终通过其自动共享意图执行至少单向通信。ATC 必须能够访问所有在空域内或计划进入其空域的 DFR 飞机的意图。虽然早期的 DFR 操作可以从双向语音通信开始，但建议最终采用自动确认机制，类似于通过数据通信为 IFR 航班进行的自动化通信传输，从而在这些空域等级进入之前有效建立 DFR 运营商和 ATC 之间的双向数据通信。此外，还建议 DFR 运营商在这些空域等级内运行时始终可以被 ATC 联系到，以便可以接收 ATC 指令。

**3.4.2. 飞行能见度**

由于 DFR 下的隔离提供基于通过合作传输的遥测和意图数据告知的自动化飞行路径管理，并在可行的情况下通过非合作传感器来增强，因此飞行能见度对隔离性能没有影响，因此与 DFR 操作的这一方面无关（类似于 IFR）。当手动飞行时，飞行能见度要求仍将适用于使用标准仪表进近和起飞程序的 DFR 飞机。否则，允许 DFR 操作在 VMC 和 IMC 中平等进行。

**3.4.3. 危险物临近**

避开天气危险、障碍物和地形是并非特定于数字飞行的操作员/飞行员责任。建议 DFR 操作可以使用其规避的传统机制（例如，视觉规避、遵守图表上的最低高度）。数字飞行社区还可以寻求其他合规方式，例如传感器技术以及将所有此类危险纳入自我隔离逻辑。然而，在其核心，数字飞行的本质是自行提供 IFR 下 ATC 提供的服务，特别是交通隔离和避免活跃的特殊活动空域。其他危险应在监管过程中确定 DFR 范围时单独考虑。

**3.4.4. 共享空域和高度**

数字飞行旨在让 DFR 运营商与 VFR 和 IFR 运营商共享空域。DFR 飞机将通过自动应用编纂的合作实践来主动避免与 VFR 和 IFR 的冲突。避免或解决冲突的行动将在 VFR 飞行员和 ATC 的正常决策范围之前采取，以最大限度地减少中断，并且解决方案（即修改后的意图）将自动共享。尽管 VFR 和 IFR 飞机在水平巡航飞行时通常通过交错的高度分隔，但它们仍然共享相同的空域。DFR 飞机也将共享相同的空域，但不希望 DFR 操作需要单独的高度，因为 DFR 隔离自动化不应该需要它。

## 3.5. 基本要素

与 VFR 和 IFR 一样，将为 DFR 运营商建立先决条件，包括设备、培训、熟练程度以及联邦监管机构与行业协商确定的其他要求。对于此一般性描述，资格侧重于 DFR 运营商需要使用的表 1 中所示的四个数字飞行基本要素。

表 1. 数字飞行基本要素

| 数字飞行基本要素                          | 目的                                                    |
| :--------------------------------------- | :---------------------------------------------------- |
| 数字信息连接和服务                      | 维护操作环境的数字模型，供决策制定自动化使用。                      |
| 共享交通意识                            | 维护相关交通的意识，以便进行冲突管理。                                 |
| 合作实践                               | 管理 DFR 操作的行为，以确保和谐地使用空域。                              |
| 隔离自动化                             | 自动化飞行路径管理中的隔离功能。                                  |

总之，这些要素构成了实现第 3.6 节中描述的数字飞行主要功能的基础。这些要素中的每一个都需要正式的基于社区的定义、需求研究以及用于认证和/或运营批准的基于性能的标准。此处提供每个要素的高级描述。

**3.5.1. 数字信息连接和服务**

在数字飞行中，飞机操作员使用自动化来计划、监视、评估、修改和协调飞机在操作环境中的飞行路径。为了执行这些功能，自动化必须维护或访问操作环境的数字模型，该模型是为飞机的特定操作量身定制的。由运营商及其服务提供商网络分发和维护，每个模型都包含从可靠、经过验证和授权的来源接收的适当当前信息。它必须包括 DFR 运营商在其决策制定中需要考虑的所有相关条件、天气、危险和约束。由于数字飞行需要前瞻性规划，数字模型将需要包含当前和预测信息，在可用的范围内（即，操作环境的数字模型在时间上向前投影）。此外，所有此类信息必须采用自动化可处理的形式，而不是仅为人类消费和解释设计的信息。例如，原始对流天气雷达返回图可能需要额外的处理才能将数据转换为自动化可用于飞行路径分析和修改的多边形或轮廓。

数字模型的信息要求源自数字飞行的独特功能。最重要的是那些与隔离功能相关的信息，包括相关交通飞机的状态向量和意图数据（如下所述），以及直接影响轨迹预测的空域和环境数据（例如，大气和风模型）。如果数字飞行还需要自动避开非交通危险（例如，危险天气、地形、障碍物），则这些也必须包括在数字模型中，作为特定对象或确保避开危险的最低操作高度。它还必须包括任何限制或以其他方式影响飞行路径规划的空域限制（例如，特殊活动空域、其他空域结构）。数字模型还应包括一般性质（例如，延误预测）或特定于航班的流程约束（例如，计划到达时间），以及所需机场的终端到达信息（例如，跑道配置、使用的进近）。运营商在飞行运行中通常使用的附加信息，无论何种操作模式，也应包含在数字模型中以方便和高效。

由于数字模型将用于安全关键型决策，因此它包含的数据必须满足某些标准，例如相关性、及时性和安全性。数字模型可以使用来自政府和监管机构批准的商业服务的数据进行填充，并且数据的可追溯性对于确保真实性和兼容性非常重要。可能还需要根据特定运营商的需求和飞机位置自定义数据。由于数据定制要求在各种类型的操作之间甚至在给定类型中的不同运营商之间会有所不同，因此不希望所有人都使用单个通用数字模型。对于大多数数据元素，这种程度的共享情况意识是不必要的。例如，一个运营商认为是危险的天气元素对于另一个运营商可能不是危险的。

一些共享的情况意识领域将很重要，需要在数字模型中维护，特别是那些与数字飞行的分离功能相关的领域。（共享交通意识是第二个基本要素；其具体信息要求在下一节中讨论。）为了确保对冲突的共同看法，数字模型必须包括对于解释共享交通数据（例如，共同位置-导航-计时参考）和准确预测轨迹（例如，共同风场模型）都很重要的数据元素。由于其庞大的多样性或专有考虑（例如，飞机性能模型），某些元素可能不适合共享。

特别重要的是机载隔离自动化与数字信息服务之间的连接机制。用于交通隔离的信息需要最小的延迟和最小的损坏可能性。对于时间关键型信息，例如交通飞机状态数据和意图变更，车辆到车辆的通信可能是确保这些质量的最直接方式。其他不太频繁更改的数据，例如风场模型数据，可能会在不产生不利影响的情况下承受一些延迟。通常，数字模型中的数据可能在飞行前加载，然后在飞行中通过空中地面连接机制以定期和异步的方式更新。需要更详细的分析来确定连接系统在可用性、完整性、安全性、带宽和可达性（例如，地理和海拔覆盖）方面的性能要求。

**3.5.2. 共享交通意识**

数字飞行提供自我隔离，这反过来又要求隔离自动化能够感知相关范围内的所有交通。在混合操作环境中，这通常包括 DFR 运营商飞机附近的所有 VFR、IFR 和 DFR 飞机，包括那些可能在其他规则下运行的飞机（例如，14 CFR 第 107 部分下的 UAS）。

由于数字飞行在 DFR 运营商及其飞机之间分配隔离功能，因此 DFR 运营商之间必须共享交通信息意识，确保给定冲突情况中涉及的所有隔离自动化系统对冲突的解释基本相同，并将做出兼容的决策。这种共享的交通意识可以通过 DFR 飞机彼此直接共享三组信息来实现：飞机状态、飞行路径意图和预期导航性能。

*   **飞机状态**——交通意识的第一个也是最关键的安全贡献是交通飞机的飞机识别和当前状态向量，即当前位置、高度、飞行轨迹、地速和垂直速度，类似于自动相关监视广播 (ADS-B) 的状态向量报告。隔离自动化至少需要此最低限度信息才能执行其预期功能。合作传输飞机状态将是首选机制，以确保监视性能满足既定标准。当前有关 ADS-B OUT 设备的法规为建立支持数字飞行的这种合作监视环境奠定了基础。可以从本文档和其他文档中得出关于性能和认证的额外要求，以确保满足预期功能。

    对于在不需要合作监视的空域中进行的 DFR 操作，将需要通过地面或机载技术采取非合作监视的替代方法。

*   **飞行路径意图**——交通意识的第二个贡献是飞行路径意图信息。DFR 被提议为一种合作运营模式，合作的基础是 DFR 运营商之间的意图共享。意图共享还可以使 ATC 的规划更加有效和可靠，因此可以促进更好的空域协调。它有助于更有效的战略冲突管理，并减少不必要的分隔提供行动。相关意图有三个域：目的地意图、近期意图和中间意图。
    *   **目的地意图**——共享目的地意图，包括预计到达时间 (ETA)，使到达流量管理者能够更好地估计需求并适应 DFR 飞机进入到达流量。未能共享目的地意图可能会危及此适应。
    *   **近期意图**——通常会期望 DFR 飞机共享近期意图，以提高隔离提供的性能，尤其是在与其他 DFR 飞机发生冲突时。可共享的近期意图的程度可能会因操作类型和战术情况而异。直线水平飞行飞机的最小近期意图将是其状态向量，在许多情况下，这足以让分离提供达到标准中建立的时间范围。对于机动飞机，共享目标状态（例如，预期的新航向或高度）可能构成足够的近期意图，以实现充分的分隔提供性能。对于未来有进行机动意图的飞机，共享一个或多个轨迹更改点将是适当的。
    *   **中间意图**——中间意图超出分隔提供的直接时间范围。如果需要共享中间意图，则需要根据运营环境进行定义。一般来说，数字飞行概念支持一系列意图共享，对于那些共享更多数量的人可能会提供额外的特权（例如，在冲突中获得优先权）。
    *  **非 DFR 意图共享**——数字飞行不建议对非 DFR 运营商施加意图共享要求或任何相关处罚。但是，任何可用的非 DFR 飞机的意图（例如，可能通过 ATC 信息服务在 IFR 飞机上获得的）都将由 DFR 飞机用于隔离提供。这将使与 ATC 的 IFR 飞机计划更好地协调，从而减少控制员的工作量。
*   **预期导航性能**——交通意识的第三个贡献是预期导航性能。共享预期导航性能对于 DFR 飞机与其他 DFR 飞机的相遇尤其重要，因为它提供了安全应用减少的分隔标准所需的信息。预期导航性能类似于 RNP，这是一种 IFR 下的结构，它限制了允许偏离指定标称路径的横向偏差。DFR 的预期导航性能可以以类似的方式构建，以限制 DFR 飞机对其共享轨迹意图的横向符合性。数字飞行会更进一步，将二维结构（即横向性能）扩展为包括垂直和沿路径维度，从而提供共享意图的完整四维 (4D) 不确定性边界。

    共享预期导航性能本质上是 DFR 运营商对其可能遇到的其他 DFR 飞机做出的承诺，这些飞机也将共享其导航性能承诺。总而言之，这些承诺能够应用针对该特定遭遇量身定制的分隔标准，从而使等效安全级别的分隔潜力大大降低。较小的分隔标准可以产生几个显著的好处：减少冲突、提高飞行效率以及显著提高隔离功能自动化时的运营交通密度。

*   **其他注意事项**——除了交通意识的这三项贡献之外，可能还需要共享可操作性和性能限制，以确保可以识别可行的冲突解决方案。例如，控制响应有限（例如，爬升/下降率有限）的 DFR 飞机在冲突中可能需要更高的优先级，或者如果它有解决问题的负担，则需要更多时间。当性能包络差异很大的车辆之间发生冲突时，这些问题尤其重要，并且标准开发需要考虑这些差异。同样，处于危急或紧急状态的飞机（例如，达到临界能量水平）将需要共享他们的情况以获得优先权，尽管这种情况应该很少见。

**3.5.3. 合作实践**

为了使分布式决策制定以安全、有组织和有效的方式进行，必须有一组所有 DFR 运营商都遵循的共享合作实践。形式化这些合作实践的机制可能会有所不同。例如，它们可以指定在法规或行业标准中，或者包含在推荐实践或社区指南中（例如，《航空信息手册》）。与 VFR 运营商通常通过解释和判断遵循合作实践的方式相反，数字飞行合作实践将被更严格地应用，大多数实践都编码在自动化中。

表 2 中显示并描述的候选合作实践集应被视为行业审议的起点。本文前面已经讨论了一些。建模和仿真将有助于改进和验证这些实践对于确保混合环境中 DFR 飞机的安全、有序和快速运行是必要的和有效的。航空界参与这些合作实践的改进和建立将确保它们在广泛意义上是公平和可接受的。

表 2. 数字飞行候选合作实践

| ID   | 合作实践                                | 目的                                                 |
| :--- | :-------------------------------------- | :--------------------------------------------------- |
| CP-A | 共享和更新意图                                | 提高可预测性、效率、稳定性和安全性。                           |
| CP-B | 及时采取行动                                |                                                      |
| CP-C | 在更改意图时尊重意图                         | 尽量减少对现有操作的干扰。                                     |
| CP-D | 尊重 VFR 和 IFR 飞机                       |                                                      |
| CP-E | 以预期精度导航                               | 提高空域容量；减少可操作冲突。                                  |
| CP-F | 应用适当的成对分隔                         |                                                      |
| CP-G | 尊重 DFR 飞机之间的通行权                   | 分散分离负担；提高安全性。                                     |
| CP-H | 在 DFR 飞机之间协调机动                    |                                                      |
| CP-I | 在受控空域中与 ATC 协调                      | 促进空域集成；最大限度地减少控制员工作量。                          |
| CP-J | 加入适当的流量管理                             | 尽量减少中断；最大限度地减少控制员工作量。                          |
| CP-K | 避免使用活动的受保护空域                       |                                                      |
| CP-L | 尊重既定的操作程序                             |                                                      |

此处提出的每一项合作实践都指定了实践（DFR 运营商或系统的行动或行为）和预期效果（一种或多种促进和谐利用空域资源或其他积极属性的结果收益）。这些应被视为需要验证，在许多情况下需要进一步规范的假设。

*   **CP-A. 共享和更新意图**
    *   **合作实践：** DFR 运营商将共享和更新其飞行路径意图，使其他参与者能够在适当的时间范围内（可能因操作类型而异）预测 DFR 飞机的未来状态。意图更新将在第一次更改机动时或之前共享。基本级别以外的意图共享不是强制性的，也不是继续遵守共享意图的义务。但是，在 DFR-DFR 冲突中，所有其他条件相等的情况下，共享较少意图的 DFR 飞机的成本可能是承担它们之间的分离负担。
    *   **预期效果：** 提高飞行路径的稳定性和效率；更早地检测到冲突；提高资源需求的可预测性；提高安全性。

*   **CP-B. 及时采取行动**
    *   **合作实践：** 当 DFR 运营商负担过重时，他们会在足够早的时间框架内解决冲突，以使另一方也不会因采取行动来解决同一冲突而承担负担。当清除了冲突的意图更改被共享时，即使初始机动被延迟，也声明冲突已解决。
    *   **预期效果：** 减少多个参与者解决同一冲突的发生次数；提高通行权实施的有效性；由于对遭遇结果的高度信任而减少工作量。

*   **CP-C. 在更改意图时尊重意图**
    *   **合作实践：** DFR 运营商不会进行机动以在已建立的时间范围内与另一架飞机的共享意图发生冲突。此防止新冲突的时间范围可能会因所涉及飞机的性能而异。两架飞机之间的每次遭遇都应调用适合该次遭遇的单一隔离标准和决策时间范围。
    *   **预期效果：** 减少冲突；减少或消除后续冲突；提高安全性和公平性。

*   **CP-D. 尊重 VFR 和 IFR 飞机**
    *   **合作实践：** DFR 运营商将在其他 VFR 和 IFR 飞机的飞行员或管制员通常采取行动的时间之前采取行动以进行分离。DFR 运营商将保持至少“与 VFR 飞机保持安全距离”，并以符合 14 CFR 91.113 中 VFR 通行权规则的方式进行机动。DFR 运营商将保持与 IFR 飞机至少标准的 IFR 隔离，及时与 ATC 共享其意图，以确保保持隔离。
    *   **预期效果：** 最大限度地减少对现有“看到并避开”和 ATC 分隔程序的更改；最大限度地减少对 VFR 和 IFR 飞机轨迹的影响；最大限度地减少非 DFR 飞行员和管制员的工作量。

*   **CP-E. 以预期精度导航**
    *   **合作实践：** DFR 运营商将确定其预期的 4D 导航精度性能，并将其作为其飞行路径意图的一部分进行共享，并符合共享的精度。
    *   **预期效果：** 较小成对分隔标准的基础。

*   **CP-F. 应用适当的成对隔离**
    *   **合作实践：** DFR 运营商将应用适合每次成对遭遇的分隔标准，仅基于电子交换的信息或接受的默认值。相关因素包括遭遇飞机的状态、意图、导航精度、性能限制和飞行规则。参见图 2。
    *   **预期效果：** 减少可操作的冲突；减少对相互冲突的不同解释；实现最小隔离，而不会损害安全性。

图 2 - 成对的分隔标准由特定遭遇定义。

*   **CP-G. 尊重 DFR 飞机之间的通行权**
    *   **合作实践：** DFR 运营商将根据既定的、电子应用的、DFR-DFR 遭遇的通行权规则，向其他冲突的 DFR 飞机让出通行权。让出通行权意味着承担解决检测到的冲突或以其他方式防止冲突形成的负担。
    *   **预期效果：** 提高安全性；减少不必要的机动；适应 DFR 飞机之间固有的性能差异；建立在分担隔离提供负担方面的透明基础。

*   **CP-H. 在 DFR 飞机之间协调机动**
    *   **合作实践：**当一架未承担负担的 DFR 飞机的飞机足够接近并承担与另一架（负担过重的）DFR 飞机发生分离损失的风险时，将应用自动协调（隐含地或明确地），以确保相互机动发生在互补的方向上。
    *   **预期效果：** 提高通行权负担分配不再适当的遭遇时间框架内的安全性；确保在两个参与者的遭遇中添加分离；减少防撞机动的发生。

*   **CP-I. 在受控空域中与 ATC 协调**
    *   **合作实践：** DFR 运营商将在 B、C 和 D 类空域的主要机场的滑行、起飞、进场和着陆操作中在 ATC 许可下运行。对于穿越 A 类和 B 类空域，DFR 运营商将共享意图，反之将在监管授权下而不是特定许可下运行。
    *   **预期效果：** 尽量减少对 ATC 到达/出发流量程序的影响；减少穿越空域的控制员和运营商工作量；减少频率拥堵。

*   **CP-J. 加入适当的流量管理**
    *   **合作实践：** DFR 运营商在打算使用 ATC 管理的、容量有限的空域系统资源时，将公平地参与相关的流量管理计划 (TMI)。增强交通流量绩效的贡献，例如满足所需到达时间 (RTA) 或采用间隔管理 (IM) [22] 程序，可以用于 DFR 运营商和 ATC 的共同优势。
    *   **预期效果：** 保护 DFR 和非 DFR 运营商之间的公平性；建立和维护稳定、可预测的流量，流入受约束的资源；在减少交通延误方面提高 TMI 绩效。

*   **CP-K. 避免使用活动的受保护空域**
    *   **合作实践：** DFR 运营商将在其活动期间保持远离已发布的受保护空域，除非与控制机构预先协调了其进入。这不仅包括特殊活动空域，还可能包括较大机场的进出港走廊。
    *   **预期效果：** 提高安全性；减少控制机构的工作量。

*   **CP-L. 尊重既定的操作程序**
    *   **合作实践：** DFR 运营商在从受控和不受控机场起飞和到达时将符合既定的操作程序。
    *   **预期效果：** 与 IFR 和 VFR 交通模式顺利集成。

**3.5.4. 隔离自动化**

前三个基本要素（数字信息连接和服务、共享交通意识和合作实践）的融合发生在第四个基本要素、隔离自动化及其在飞行路径管理中的作用。DFR 运营商使用隔离自动化来建立和维持在受限交通和危险环境中安全飞行的飞行路径。此自动化系统是数字飞行的合作、自我隔离能力的执行器。在飞行过程中，DFR 运营商与隔离自动化的交互方式与 IFR 飞行员与 ATC 的交互方式大致相同。自动化作为 DFR 运营商的工具，用于检测交通冲突、确定机动负担以及计算所需的飞行路径更改，以在满足操作环境和飞机性能限制的情况下解决冲突。合作实践被嵌入到隔离自动化的逻辑中，以确保好的，继续翻译接下来的内容：

一致地应用这些实践，并减轻人类操作员记住或解释它们的负担。在达到 DFR 运营商/飞行员可以通过视觉或程序避免危险的条件之前，自动化确定要执行的任何机动（或不执行）。运营商通过飞行员操作或指定的自动飞行执行功能来确保机动的实施。

隔离自动化还会评估用户对飞行路径的任何建议更改（例如，期望的航向或高度更改），以确保保持隔离。隔离自动化还提供约束合规性，例如尊重空域结构或满足 RTA。这些功能与隔离功能相互作用，因此必须集成到自动化功能设计中。

隔离自动化在飞行过程中的主要功能是四重的：监视飞行路径相对于任务目标、操作环境、约束和其他因素；评估飞行路径的持续可操作性；在需要时修改它以维持一组期望的品质；并与其它空域用户和服务提供商协调飞行路径更改。飞行路径的理想品质是可操作性、无冲突性、协调性、灵活性和最佳性。可操作的飞行路径在飞机的性能和航程范围内，并且符合空域限制、固定障碍物和地形以及时间限制。无冲突的飞行路径在适当的时间范围内和隔离标准内，不会与交通、危险天气和其他动态约束发生冲突。协调的飞行路径满足合作实践的要求。灵活的飞行路径具有足够的调节性，可以在必要时进行未来的更改（例如，解决后来的冲突）。最佳飞行路径在所有其他约束条件下尽可能满足运营商的业务目标，包括系统级优化考虑。参考文献 [23] 提出了支持动态、飞行中路径规划的隔离自动化的正式系统概念描述。

在数字飞行中，隔离自动化的托管位置将由运营商决定。这种灵活性是有意的，以适应适合运营商或操作类型的各种候选系统架构（参见图 3）。例如，运营商可以将自动化托管在机载、运营商的地面控制设施中，甚至是云服务中。无论选择哪种架构，都至关重要的是，端到端系统完整性要满足已建立的性能标准，鉴于隔离功能的时间和安全关键性。例如，非飞机托管位置将依赖于高度可靠的空对地通信链路，以实现与飞机飞行控制系统的无中断、安全和低延迟连接。根据成本和其他因素，在多个位置托管自动化可能更好地满足性能要求。

进一步推动数字飞行在系统架构方面的有意灵活性的是，运营商可以选择自行提供基本要素，或者通过政府或商业服务提供商获得这些要素的一部分。虽然 DFR 运营商保留对运营安全（包括交通隔离）的最终责任，但对于某些 DFR 运营商来说，通过获得的服务来满足此责任可能在经济上更具优势。一个类似之处是飞机维护、修理和大修 (MRO)，其中一些运营商在内部托管 MRO 功能，而另一些则使用受监管的商业提供商。在这两种情况下，运营商仍然负责飞机的适航性。在数字飞行中，责任被设定为更高的标准，鉴于飞行路径决策的实时运营和安全影响。因此，数字飞行中服务提供商的作用可能侧重于信息和服务协调，而运营商管理与合作隔离提供相关的决策制定。无论如何，数字飞行允许一系列自助服务和获得的服务。

图 4 显示了合作自我隔离过程的表示。所有四个基本要素都包含在这个概念性的过程中，从维护操作环境的数字模型和共享运营意图，到应用合作实践来管理冲突。此处没有说明 DFR 操作的所有方面，例如与 ATC 的协作交互和符合运营约束。

图 3. 隔离自动化可以包括连接到各种数据源的机载和/或地面组件。
图 4. 数字飞行中合作自我隔离的代表性过程。

## 3.6. 主要功能

利用上一节中描述的四个基本要素，数字飞行提出了一组候选的运营功能，这些功能共同使 DFR 能够提供相对于其他可选模式的独特运营价值。本节介绍了最初的一组六项数字飞行主要功能，并认识到，随着获得 DFR 的运营经验和进一步创新应用，可能会出现其他功能。表 3 总结了以下详细介绍的六项主要功能。

表 3. 数字飞行的主要功能

| 功能           | 启用操作                                                                                             |
| :------------- | :------------------------------------------------------------------------------------------------- |
| 操作员自我隔离      | 使 DFR 运营商能够提供他们自己的隔离，而不是 VFR 的视觉程序和 ATC 的分隔服务。                                 |
| 合作冲突管理     | 使 DFR 运营商能够彼此协调，以公平安全地共享或分担隔离负担。                                                    |
| 自适应成对隔离     | 使 DFR 运营商能够根据每次遭遇情况调整分隔标准，从而有可能显著减少 DFR 飞机之间的隔离，而不会损害安全。                        |
| 约束资源的协作利用 | 使 DFR 运营商能够与 ATC 在受控机场的进港流量同步和需求容量平衡方面进行协作。                                            |
| 自我组织和排序     | 使 DFR 运营商能够在 IMC 中，以有序、自我组织的方式到达和离开非塔台机场。                                                |
| 密度和操作复杂性的自我调节   | 使 DFR 运营商能够在扩展到日益复杂的环境的同时维持安全运行。                                                       |

前三项列出的功能被认为是数字飞行的基本功能，因此建议所有 DFR 运营商都必须具备。第四项列出的功能适用于打算使用 ATC 管理的机场资源的运营商，并且可能需要这些 DFR 运营商使用。其余两项列出的功能是推测性的功能（即可能需要进行额外的研究，因此需要更长时间才能实现），但被认为有助于实现 DFR 运营的全部可扩展性收益。

**3.6.1. 操作员自我隔离**

> DFR 运营商的能力是直接确保与已知交通和危险保持至少最低可量化位移，无论是在 VMC 还是 IMC 中，还是在与 VFR、IFR 和其他 DFR 飞机共享的空域中。

如图 5 所示，此功能是 DFR 运营安全进行并放弃需要与 VFR 和 IFR 运营隔离的主要机制。此功能将 DFR 与 VFR 的主观“看到并避开”能力和 IFR 通过强制性 ATC 主动控制提供的隔离服务区分开来。交通隔离是此功能的重点，但所有物理和运营危险（例如地形、障碍物、天气和受保护的空域）都可以包含在其结构中。隔离提供通常通过动态计算技术执行，包括飞行路径建模、无冲突机动、冲突检测和计算解决方案机动。

第 3.5 节中描述的四个基本要素确立了此功能（以及其余功能）所需的必要信息、功能和行为规则。特别是，第 3.5.3 节中的合作实践在整个过程中发挥着重要作用。例如，合作实践 B (CP-B) 要求 DFR 运营商“及时采取行动”。因此，自我隔离能力应用适当的时间范围和预测不确定性缓冲区，以确保及时和明确的冲突管理。CP-D 要求 DFR 运营商“尊重 VFR 和 IFR 飞机”。因此，DFR 运营商将保持至少“与 VFR 飞机保持安全距离”（通过数字而不是视觉方式），以符合 14 CFR 91.113 中的 VFR 通行权规则的方式进行机动。同样，DFR 运营商将保持与 IFR 飞机至少标准的 IFR 分隔，及时与 ATC 共享他们的意图，以确保维持隔离。

图 5. 数字飞行的操作员自我隔离能力确保与交通和其他危险保持足够的位移。

当 DFR 运营商未在特定许可下运行时（即，由管制员在特定飞行时通过呼号向特定航班发出的许可，如第 3.4 节中所述），则始终应用自我隔离能力。对于从非塔台机场起飞的运营，自我隔离从跑道（或停机坪）占用开始，并持续到起飞。在塔台机场，它在 ATC 起飞许可终止时开始。类似的责任期限适用于到达，具体取决于是否在特定许可下运行。

为了与非交通危险自我隔离，DFR 运营商可以选择应用非数字技术。这些可能包括程序方法，例如遵守监管机构发布的用于地形和障碍物规避的最低高度和仪表进场/离场程序，或者如果使用 VMC 运行，则应用视觉隔离。或者，操作员可以使用交通隔离中使用的相同数字（即动态、计算）技术，从而将所有危险规避集成到一个公共机制中。这种不同可接受的合规方式的灵活性旨在支持更广泛的 DFR 运营，因为并非所有危险都平等地适用于所有类型的运营。例如，CP-K“避开活动的受保护空域”确保 DFR 运营商在适用时将其纳入其飞行路径规划和监控功能。

DFR 的授权（由自我隔离能力启用）还使操作员能够动态地进行自我优化，以实现业务目标，例如节省燃料或时间，在不干扰的基础上（即，在交通、危险和其他适用的空域系统和流量管理限制定义的自由度内）。类似这样的自我优化能力存在于 VFR 和 IFR 中，但在 VFR 下仅限于 VMC，并且在 IFR 下需要 ATC 批准。在 DFR 下，操作员有能力在没有这些约束的情况下进行自我优化。

**3.6.2. 合作冲突管理**

> DFR 运营商能够公平地共享或分担隔离提供的负担，从而最大限度地减少相互影响的情况下共享空域。

如图 6 所示，这种能力通过添加 DFR 运营商可以相互应用的通用程序来协同增加他们的操作员自我隔离能力，以增加他们的运营效率，最大限度地减少重复努力或其他不必要的操作，并在彼此靠近运行时增强安全性。这些通用程序在第 3.5.3 节描述的合作实践中捕获。

CP-A 要求 DFR 运营商“共享和更新意图”。这种做法通过在合作方之间公开意图来建立合作的基础，反过来又允许更好的规划。例如，与附近的 DFR 飞机共享即将到来的转弯，可以提高接收者的数字情况意识，并使其自动化能够评估该转弯对其自身飞行的影响。它可能会允许更早地检测到冲突，从而实现更有效的解决方案，或者它可能会完全消除冲突及其所需的行动。在大量相邻的 DFR 飞机中，意图共享可以提高稳定性并减少空域中不必要的机动。

CP-C 指示 DFR 运营商“在更改意图时尊重意图”。此项合作方式与之前的合作实践很好地一致，建立在意图共享为飞机提供一定程度的优先级，同时遵守该共享意图。因此，其他 DFR 飞机通过不进行机动来造成与该飞行路径的冲突来配合。防止冲突与解决冲突同样是隔离提供的一部分。

图 6. 数字飞行运营商在冲突管理中合作以公平安全地分担负担。

进一步提高公平性和增加稳定性的是 CP-G 的应用，“尊重 DFR 飞机之间的通行权”。虽然无意让 DFR 改变 14 CFR 91.113 中为 VFR 和 IFR 飞机建立的通行权规则，但可能有必要建立专门适用于在 DFR 下运行的飞机之间交互的通行权规则。这些规则的主要目的是明确地为给定的 DFR-DFR 遭遇分配分离负担。在这方面进行合作可以使未承担负担的飞机保持其首选飞行路径，同时建立一种公平机制（即，在另一次遭遇中，角色可能会颠倒）。如果分担机动负担，但一架飞机未能或延迟其机动，它还可以降低相互依赖的安全性风险。通行权规则还提供了一种将其他因素纳入优先级分配机制的方法，例如飞机性能。通过这些规则的数字应用，可以轻松地合并各种复杂因素。

对于高度接近的冲突，CP-H 规定 DFR 运营商“在 DFR 飞机之间协调机动”。对于足够接近分离损失的冲突，此要求假定两架飞机现在都必须进行机动以确保实现所需的分隔。这里的合作要素是每个飞机机动方向的协调，以确保它们的机动是互补的（即，朝向隔离目标增加而不是无意地减少）。协调是自动化的，可以采用隐含或明确的形式。隐含的机动协调是通过监管机构批准的逻辑在每个飞机的分离自动化中实现的，该逻辑基于已共享的信息（例如，作为常规遥测共享的状态向量）选择互补的机动方向。明确的机动协调包括为就该遭遇达成协议而进行的额外成对通信。

**3.6.3. 自适应成对隔离**

> DFR 自动化根据特定成对因素调整隔离标准的能力，从而安全地减少隔离以提高运营效率和空域容量。

这种在比 IFR 分隔使用的标准更小的分隔标准下安全运行的能力是数字飞行被设想能够以高得多的交通密度进行运营的关键机制之一。与对所有遭遇使用少量固定分隔标准（如 IFR 所做的那样）相反，此数字飞行功能使用意图和导航精度的合作共享来得出特定于并适合于每次遭遇的分隔标准，如图 7 所示。这种合作信息共享使 CP-F 成为可能，“应用适当的成对分隔”。由于其合作要求，此 DFR 功能适用于 DFR 飞机之间的遭遇。通过合作实践 CP-A“共享和更新意图”和 CP-E“以预期精度导航”，DFR 飞机彼此通信其计划飞行路径以及他们打算以多精确的方式符合这些路径。

预期导航符合性类似于 RNP，但有两个区别。首先，数字飞行没有“要求”的导航性能。相反，DFR 运营商确定其自己飞机的导航性能能力，并将其作为意图消息的一部分进行共享，本质上是作为对其他邻近 DFR 飞机的自我声明承诺。其次，必须在多个维度上指定导航一致性，而不仅仅是 RNP 的横向维度，因为此信息将确定与任意几何形状的遭遇的分隔标准。具有更严格的 4D 一致性承诺的 DFR 飞机是应用更小分隔标准的候选者，尽管实际值将取决于两架飞机的导航性能。此外，由于分隔风险承受能力可能因运营商或操作类型而异，而与导航性能无关，因此这种风险承受能力可以纳入预期的导航性能消息中。因此，每次遭遇都有其自己的分隔标准，适用于成对的性能和所涉及飞机的隔离风险承受能力。

图 7. 数字飞行使能够根据每次遭遇的独特属性调整分隔标准。

**3.6.4. 约束资源的协作利用**

> DFR 运营商通过提供其飞机可靠的未来状态来与到达流量管理协作的能力，以实现更有效地使用容量有限的空域资源。

此功能使 DFR 运营商直接参与流量同步和需求容量平衡的战略冲突管理功能，从而有利于到达运营的效率和所涉人员的工作量。任何到达需求超过着陆速率容量的机场都有资格使用 TFM 来将到达流量调整到最大化吞吐量和最小化延误的适当水平。随着 TFM 中动态调度方法的使用越来越广泛，DFR 运营商将带来协作能力，通过精确、无冲突的到达性能来增强这些方法，如图 8 所示。

合作实践 CP-J“加入适当的流量管理”与此功能保持一致。合作早在到达之前就开始，在某些情况下甚至在起飞之前就开始，DFR 运营商共享其预期的目的地、ETA 和首选到达固定点/跑道/停机坪。此信息允许 TFM 进行更准确的需求估计，从而更好地进行调度。来自 DFR 运营商的航路 ETA 更新将随着不确定性的减少而使计划得到完善。DFR 运营商应用其 4D 符合性能力，并致力于实现精确和可靠的到达状态，从而协作地增强 TFM 性能。

图 8. 数字飞行运营商通过提供可靠的状态（如 RTA 会议和间隔管理）与流量管理者进行协作。

**3.6.5. 自我组织和排序**

> DFR 运营商能够执行分布式本地交互，以在飞机之间创建秩序以满足共享的运营目标，通常是着陆的排序和间隔。

此推测性的数字飞行功能使 DFR 运营商能够在没有中央机构为该资源提供调度或排序的情况下共享容量有限的资源。类似于在流行的不受控区域进行的 VFR 运营，其中通过既定程序、交通模式、无线电语音程序和视觉获取来定期执行自我组织和自我排序，此数字飞行功能符合这些程序，并将操作扩展到 IMC 中，同时主要依赖于自动数字交换。分离自动化算法处理关于动态运营环境和本地交通的信息，并确定其飞机在到达顺序中的适当位置。意图共享消除了歧义，包括潜在地声明要遵循的交通飞机。序列冲突通过预先建立的优先级规则自动解决。与到达的 VFR 和 IFR 飞机的交互类似，应用 CP-D “尊重 VFR 和 IFR 飞机”和 CP-L“尊重既定的运营程序”来确保其操作的兼容性。

自我组织和自我排序的能力也可能适用于非受控机场以外的环境。例如，如图 9 所示，遇到对流天气的 DFR 运营商可以使用此能力来组织和排序自己，通过天气缺口进行飞行。是否需要单独的自动化功能来管理此方案将取决于自我隔离能力的新兴行为，在这种情况下，冲突解决会自然形成交通的排序，因为一架飞机让另一架飞机先行。

图 9. 可能会开发数字飞行来产生自我组织的行为。

**3.6.6. 密度和操作复杂性的自我调节**

> DFR 运营商能够在分布式、自动化的方式中应用适当的缓解措施，随着交通量增加，确保安全运营以保持规模。

这种数字飞行能力也具有推测性，这归因于 DFR 运营商的集体能力，以确保他们的自我隔离能力在飞机密度或其相互作用的复杂性增加时保持可行。这种能力类似于每个 ATC 扇区容量的静态实施，但具有重要的差异。它不是对飞机数量或密度应用静态上限，而是动态的，并且针对数字飞机的隔离提供机制量身定制（即，分布式、合作、自动化和基于轨迹的）。与 IFR 不同，在有多少 DFR 飞机可以共享空域以及配置方面，人类的工作负荷不太可能是一个考虑因素，频率拥堵也不是。相反，最重要的是保留为了执行自我隔离的未来飞行路径更改的灵活性。如图 10 所示，只要 DFR 程序确保有足够的机动空间和决策时间，自我隔离的性能应该可以维持在比今天常见的交通密度和复杂性更高的水平。

在 DFR 操作的早期阶段，在此功能成熟之前，可能适合应用经验表明可以由自我隔离管理的简单容量限制。但是，在长期来看，应用适用于以人为中心的 ATC 的技术将对数字飞行产生适得其反的结果。因此，开发此数字飞行能力对于实现数字飞行固有的可扩展性优势非常重要。

图 10. 数字飞行可能应用更长的提前期和无冲突的机动保护来自我调节交通密度和复杂性。

## 3.7. 系统安全考虑

系统安全是数字飞行实施的一个重要方面，既适用于在 VFR 和 IFR 下获得运营信用，也适用于在 DFR 一旦确立为受监管的操作模式之后在 DFR 下进行的运营。本节讨论了未来功能危害评估 (FHA) 和初步系统安全评估 (PSSA) 的考虑因素，这些评估将是认证和批准系统、设备和程序（允许在 DFR 下进行操作）所必需的。

此处考虑的主要安全要求在共识标准 14 CFR 23.2510 以及相应的第 23.1309 和 25.1309 部分（设备、系统和安装）中捕获。相关指导材料（例如咨询通告 (AC) 23.1309-1E（23 部分飞机的系统安全分析和评估））反过来调用航空推荐实践 (ARP) 4761（关于在民用机载系统和设备上进行安全评估过程的指南和方法）。

以下部分描述了适用于 DFR 评估的系统安全评估过程的要素。该过程需要识别和分类危险、其缓解措施及其相关概率。总而言之，这些因素定义了与 DFR 相关的风险，从而定义了所需设备的**设计保证级别 (DAL)** 和认证路径，以及与其使用相关的必要名义和非正常操作程序。与所有操作模式一样，DFR 依赖于人和技术，两者都可能出错。因此，分析应包括技术、人为因素和运营因素的组合，这些因素会导致以下已识别的 DFR 危险和潜在缓解措施。

**3.7.1. 系统故障**

在大多数情况下，如果系统故障导致隔离功能丧失，可以使用现有的操作模式（例如，VFR、IFR）作为 DFR 的后备方案。最关键的情况发生在数字飞行系统在 IMC 中出现故障时，此时 ATC 本来会提供隔离（如果飞机要在 IFR 下运行）。在最糟糕的情况下，此类故障可能是潜在的（未显示），从而阻止操作员进行检测。这种情况与 IFR 通信丢失状态或 VFR 飞机在不知道通信丢失的情况下（直到试图发出控制指令或转移通信时）非常相似。

几种缓解措施降低了与此危险相关的风险，包括建立足够的 DAL、系统冗余，以及作为最后的手段，向 DFR 飞行发出防撞系统操作，该系统必须在功能上独立于 DFR 隔离提供系统及其计算。当 DFR 系统不是代替 ATC 提供分离功能的唯一手段时，风险会显著降低，例如在 VMC 期间 DFR 上有飞行员的情况下。在这些情况下，运营商可以立即进行干预并在保持视觉条件下重新承担视觉隔离的责任。

正如管理 IFR 和 VFR 航班的飞行中紧急情况和系统故障的程序一样，DFR 可能需要额外的规定，以利用数字飞行能力。对于各种 DFR 遭遇和操作，可以考虑可能发生隔离提供系统故障的几种情况：(1) DFR-DFR 遭遇；(2) DFR-VFR 遭遇；(3) DFR-IFR 遭遇；以及 (4) DFR 接近着陆。每种情况都会对主要的 DFR 飞机和其他受影响的飞机产生不同的后果。在情况 (1) 中，如果主 DFR 飞机的 DFR 系统发生故障，其他 DFR 飞机的系统将确保与发生故障的 DFR 飞机隔离，将其视为未按要求执行的“不合作”交通。在情况 (2) 中，VFR 交通永远不会失去看到和避开交通的责任，并且发生故障的 DFR 飞机将简单地恢复为 VFR 程序。情况 (3) 更加关键，但这与飞机失去 RNP 或 RVSM 能力的情况完全类似：运营商有义务立即通知 ATC，并将获得在 IFR 下继续运营的许可。ATC 将承担 IFR 飞机和发生故障的 DFR/新 IFR 飞机的隔离责任。情况 (4) 是其他情况的组合，如果 DFR 飞机从前方交通提供拖曳隔离，则可能只会导致问题。在这种情况下，可以通过程序方式（例如，通过口头协调进行地速控制）或通过恢复为 ATC 控制或 VFR 操作来实现隔离。在 ATC、IFR 和 VFR 标准中，使用程序来缓解飞行中紧急情况是一种完善的做法，并且将是 DFR 的一致方法。

**3.7.2. 监视故障**

DFR 监视故障会导致 DFR 飞机失去共享的交通意识，这将禁用上述讨论的隔离功能。通过系统冗余和使用不同的数据源（例如，ADS-B 和宽带）可以缓解这些影响。数据源的冗余和支持能力的弹性技术对于实现弹性功能和尽量减少使用后备措施的需求至关重要。即使有冗余，系统范围的监视故障也会对所有受影响的飞机（DFR 和非 DFR）产生深远的影响。这种性质的灾难性故障已经在 NAS 的结构中得到解决，并且被缓解到适当的远程概率。

**3.7.3. 显示和告警故障**

DFR 系统显示和告警故障可能导致隔离功能的有效丧失，如上所述，或飞行员/操作员态势意识的丧失，这增加了与系统交互时人为错误的几率。故障分为两大类：功能丧失和危险地误导性信息的显示。在影响单个 DFR 飞机的部分功能丧失后，运营（在没有冗余系统的情况下）将恢复为替代运营模式（VFR 或 IFR），对 ATC 或其他用户的影响最小。危险误导性情况更为严重，因为它有可能导致 DFR 系统或 DFR 运营商做出可能危及安全的错误决策。这将再次通过实现适当的 DAL 和系统冗余以及通过合并经过验证的缓解措施（例如独立内置检查和电子“心跳”监视器，这些监视器会在冻结时关闭受影响的系统）来解决。此类故障的残余风险应与影响单源全球定位系统 (GPS) 导航器的风险相当，该导航器被完全接受用于执行安全关键功能，例如在 IMC 中接近最低点。

**3.7.4. 通信故障**

数字飞行不依赖于口头通信，并且在通信丢失的情况下可能比传统系统更可靠。DFR 将需要一定程度的数据链路通信，并且其影响将取决于中断的程度和持续时间。这种影响将通过机载系统冗余和接收所需数据的多条路径来缓解。此外，可以设计隔离自动化来维护最小的分隔时间范围，这将确保在发生故障后，已知交通在指定时间内不会发生冲突。这将为 DFR 运营商提供时间来过渡到替代运营模式，而不会危及隔离。GPS 进场期间丢失接收器自主完整性监控 (RAIM) 时会采用类似的概念：如果在最后进场航路点之后发生 RAIM 故障，则允许接收器在不发出公告的情况下继续操作最多五分钟以完成进场 [24][25]。

**3.7.5. 人为错误**

人类错误已分为失误、疏忽、笨拙、错误和程序违规 [26]。DFR 运营商可能会受到每种类型错误的影响。当数字飞行系统自主运行时（即，没有操作员直接干预），人类操作员在执行警戒任务时承担监督角色。人类不擅长这个角色，这会促进疏忽，因此将对隔离自动化进行工程设计，以使飞行员或操作员在需要快速干预时保持高度态势意识。尽管如此，经过适当设计的数字飞行系统不会遭受典型的人为错误，从而为组合的操作员/数字飞行系统带来更大的整体安全性。

总之，传统的风险缓解方法，例如建立合适的 DAL、系统冗余、弹性架构、恢复为 VFR 和 IFR 以及现有的 NAS 稳健性，将使 DFR 运营能够安全且稳健地进行。在大多数情况下，由于 DFR 运营对隔离提供中人类要素的依赖性降低，因此 DFR 运营比非 DFR 运营更不容易受到故障的影响。


## 3.8. 低空数字飞行

在通用数字飞行的基础上，低空数字飞行呈现出一系列独特的挑战和机遇，需要更加精细化和高度适应性的解决方案。这些特点直接影响了低空空域的运营模式、技术要求以及监管框架。

**3.8.1. 低空空域的独特性：复杂、多变和拥挤**

- **地形复杂：** 低空空域通常位于地表附近，地形起伏不定，包括山丘、峡谷、河流、湖泊、植被和建筑物等，这些地形特征对飞行路径规划、障碍物规避和导航精度提出了更高的要求。数字飞行系统必须能够精确地建模和解析这些复杂的地形特征，并为飞行器提供实时的动态路径规划。

- **障碍物多样：** 低空空域的障碍物种类繁多，包括高压电线、发射塔、建筑物、树木、桥梁以及各种移动物体（如车辆、行人和动物）等。数字飞行系统不仅需要能够识别和跟踪这些障碍物，还需要预测其行为，并及时提供规避建议。

- **气象条件多变：** 低空空域的气象条件通常更加多变和难以预测，包括阵风、乱流、低云、降水、温度变化等。这些气象因素可能会对飞行器的稳定性、能见度以及通信链路的可靠性产生重大影响。数字飞行系统必须能够收集和处理各种气象信息，并对环境变化做出快速响应，以确保飞行安全。

- **非传统飞行器共存：** 低空空域预计将是各种非传统飞行器运营的场所，包括小型无人机 (sUAS)、垂直起降 (eVTOL) 飞机、高空平台系统 (HAPS) 等。这些飞行器具有不同的性能包络、操作需求和通信协议，必须在共享的低空空域中实现安全有效的共存。

**3.8.2. 高密度和多模式运营：安全有序的复杂环境**

- **高密度：** 低空空域预计将支持高密度的飞行活动，尤其是在城市区域，大量的无人机可能在同一空域内执行各种任务（例如，包裹递送、监视、建筑检查、农业喷洒等）。这需要数字飞行系统能够有效管理高流量环境，并确保所有参与者能够安全有序地运营。

- **多模式：** 低空空域中将存在各种类型的飞行器，包括小型无人机、大型无人机、eVTOL 飞机、传统有人驾驶飞机和轻型飞机等。这些飞行器具有不同的性能特征、速度和操作模式，需要数字飞行系统能够提供适应不同类型飞行器的操作能力，并确保它们之间的安全分隔。

- **动态任务：** 低空空域的任务特性是高度动态的，例如，包裹递送任务需要在不同的地点进行起飞和着陆，而巡检任务则需要在不同的地点进行飞行或悬停，并且需要快速调整航线。数字飞行系统必须能够支持这些动态任务，并确保在变化的环境中能够安全高效地执行。

**3.8.3. 超视距运营：可靠通信和监视的关键**

- **BVLOS 的需求：** 许多低空应用（例如，长距离包裹递送、基础设施巡检、环境监测、灾难响应等）需要在超视距 (BVLOS) 的条件下进行运营，这需要在运营商无法直接看到飞行器的情况下进行远程控制和操作。

- **可靠通信：** 为了支持 BVLOS 操作，数字飞行系统需要建立可靠的、低延迟的通信链路，以便在飞行器和地面控制站之间传输飞行指令、状态信息和交通态势。这需要使用各种通信技术（如蜂窝网络、卫星通信或专用数据链路）和冗余机制来确保链路的可靠性和连续性。

- **准确监视：** 对于 BVLOS 操作，仅靠机载传感器无法提供全面的交通态势感知。数字飞行系统需要整合来自各种来源的监视数据，包括机载传感器、地面雷达、合作监视系统（如 ADS-B）和第三方服务提供商，以便能够感知周围的飞行交通并预测潜在的冲突。

**3.8.4. 城市环境中的挑战：应对复杂和拥挤的区域**

- **建筑物干扰：** 在城市环境中，建筑物可能会对 GPS 和其他导航信号产生干扰，并导致飞行器迷失方向或无法进行准确导航。数字飞行系统需要能够使用多种导航技术并使用辅助定位方法，例如使用视觉定位或者与已知的建筑物数据进行比对，以确保在 GPS 信号不可靠的区域仍然能够安全飞行。

- **人口稠密：** 城市中心的人口高度密集，这使得在发生意外情况时需要确保地面人员的安全。数字飞行系统需要能够准确预测飞行路径和潜在的坠落地点，并根据需要重新规划路线，以最大程度地减少对地面人员的风险。

- **射频拥堵：** 城市区域的射频频谱通常非常拥挤，因为存在各种通信系统（包括移动电话、无线网络和广播）。数字飞行系统需要能够有效地管理频谱拥堵，并确保它们的通信链路不会受到干扰。

- **有限的导航资源：** 城市环境中，传统的导航资源（如机场信标和无线电导航台）可能不适用或无法使用，因此需要数字飞行系统采用更加先进的导航技术，例如基于视觉的导航和基于传感器的导航。

**3.8.5. 社区融合：建立公众的信任和理解**

- **透明沟通：** 低空数字飞行的广泛应用将对当地社区产生影响。监管机构和运营商必须积极主动地与社区成员沟通，公开透明地讨论数字飞行的潜在好处和风险，并解释 DFR 的应用和法规要求。

- **解决担忧：** 社区成员可能会对噪音、隐私、安全和潜在的环境影响表示担忧。监管机构和运营商必须倾听和解决这些担忧，并采取措施来最大限度地减少负面影响，包括技术改进、优化操作程序，以及实施相关的补偿措施。

- **促进理解：** 为了促进社区对数字飞行的理解，监管机构和运营商可以开展教育活动，向公众解释这项新技术的运作方式、安全机制和预期收益。

**3.8.6. 精细化流量管理：有效利用低空空域**

- **动态调整：** 传统的流量管理方法主要集中于大型机场，而低空数字飞行需要更灵活的流量管理方法，能够适应各种飞行器的动态任务和运营模式。

- **实时优化：** 为了在拥挤的低空空域中最大限度地提高容量和效率，数字飞行系统需要能够实时优化流量，并根据交通流量的动态变化进行调整。

- **公平资源分配：** 数字飞行需要确保所有运营者能够公平地访问低空资源，并避免歧视特定类型或规模的运营。

**3.8.7. 自动化流程：**为了应对低空交通管理的复杂性，数字飞行需要高度依赖自动化，包括动态调度、冲突解决和路径规划等功能，从而减少人工干预的需求。

**3.8.8. 能源管理：高效、可持续的低空运营**

- **能量限制：** 由于体积和重量限制，低空飞行器，特别是电动飞机，通常具有有限的能量存储能力。数字飞行系统必须能够优化能源使用，从而最大限度地延长续航时间，提高运营效率。

- **航线优化：** 通过对飞行路径、飞行高度和速度进行优化，降低飞行器的能源消耗，最大限度地提高任务的完成效率，数字飞行系统可以有效地降低能源成本。

- **动态能源管理：** 数字飞行系统应能够根据飞行器的能耗、任务需求和环境条件实时调整电力分配，从而确保能源的合理有效利用。

- **电池监控和优化：** 精确跟踪电池的充电状态，预测可用的续航能力，并根据需要调整任务目标和运营策略，以最大限度地延长飞行时间，也是非常重要的。

低空数字飞行在提供机遇的同时，也带来了前所未有的复杂性，需要更加注重其鲁棒性、适应性和对未来各种运营场景的灵活性。数字飞行将需要在复杂的低空环境中确保所有参与者的安全，并将通过更积极的社区沟通和协作，促成低空经济的积极发展。