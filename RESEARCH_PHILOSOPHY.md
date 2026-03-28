# Research Philosophy

This project begins with a simple but enduring belief:

That **ambition gives direction**,  
that **courage sustains exploration**,  
and that **reading is often the first act of serious thinking**.

Long before models, benchmarks, or systems, research starts with curiosity —
a willingness to question what is known, to read deeply, and to imagine what might be possible.
Books, papers, and ideas encountered through reading do not merely transmit knowledge;
they quietly shape how we see the world, how we frame problems,
and how far we are willing to think beyond established boundaries.

Pursuing research, especially in emerging fields such as GeoAI and AI4Science,
requires a particular kind of courage:
the courage to cross disciplines,
to work at the intersection of geography, artificial intelligence, and Earth system science,
and to accept uncertainty as an essential part of discovery.

This repository is built not only as a collection of resources,
but as a reflection of a research journey guided by **intellectual ambition**,
sustained by **curiosity and courage**,
and continuously refined through **reading, learning, and critical reflection**.

What follows is both a map of ideas and an invitation:
to read carefully, to think spatially,
and to explore how autonomous intelligence can deepen our understanding of the Earth and its complex systems.<br>
很抱歉我会用我的母语（中文）来写我的研究哲学，翻译是极其简单的事情。如果你渴望了解，请翻译。

## 什么是我的博士专业？
在当今社会，地理信息科学（Geographic Information Science, GIScience）及其与人工智能深度融合形成的地理人工智能（GeoAI），在理解复杂社会—环境系统、支撑公共决策以及应对全球性挑战方面发挥着日益关键的作用。首先，现代社会正处于一个高度空间化与数据化的时代。城市运行、交通系统、公共健康、气候变化、自然灾害以及社会不平等等问题，本质上都具有显著的空间与时间特征。GIScience 通过对空间数据的采集、建模与分析，为我们提供了一种系统性理解“事物发生在何处、如何相互关联以及随时间如何变化”的科学方法。这种空间视角不仅帮助政府和研究机构更准确地识别问题分布，也为资源配置和政策制定提供了可靠依据。其次，随着大数据与人工智能技术的发展，GeoAI 正在显著提升地理信息科学的分析能力和社会影响力。通过将机器学习、深度学习等方法引入空间数据分析，GeoAI 能够从海量、多源、异构的数据中自动发现模式与规律。这对于灾害风险评估、气候适应、公共健康监测以及城市韧性建设尤为重要。例如，在自然灾害发生前后，GeoAI 可以快速整合遥感影像、街景数据和社会感知数据，为应急响应和灾后恢复提供高时效、高精度的空间支持。此外，我所学习的这一专业在促进社会公平与可持续发展方面也具有重要意义。通过精细化的空间分析，GIScience 和 GeoAI 能够揭示不同群体在环境暴露、健康风险和公共服务可达性方面的差异，从而为弱势群体发声，并推动更加公平和负责任的决策。这种以数据和空间证据为基础的方法，有助于缩小社会不平等，增强社区层面的韧性。最后，在人工智能快速发展的背景下，地理信息科学不仅关注“技术能做什么”，也强调“技术应该如何被使用”。将空间智能与人类判断相结合，确保分析结果可解释、可审计，并服务于公共利益，是该领域的重要使命。因此，我的专业不仅是技术导向的学科，更是一门与社会责任、公共治理和人类福祉密切相关的交叉科学。综上所述，地理信息科学与地理人工智能在当今社会中具有不可替代的重要性。它们为理解复杂世界提供了空间化的科学框架，为应对灾害、气候变化和社会不平等等重大挑战提供了关键工具，也为构建更加安全、公平和可持续的未来奠定了坚实基础。--ChatGPT-5.2


## What is disaster resilience? What are the major/important tasks in disaster resilience? What are the data/model challenges in supporting these tasks?
From a geographical perspective, disaster resilience is essentially the spatiotemporal adaptability of a Human-Environment System. It involves three environments and three types of systems: the natural system (climate, topography, ecology), the built environment (cities, transportation, electricity, buildings), and the social system (population, economy, governance capacity). Disaster resilience refers to the ability of a socio-ecological-infrastructure system to withstand, adapt to, recover from, and sustain itself in the face of natural disasters. Simply put, it answers four questions: Can it withstand a disaster? How will it respond when a disaster strikes? How quickly can it recover after a disaster? And can it become stronger in the future?

Disaster resilience typically revolves around the disaster lifecycle:
1. Risk Identification
Goal: Identifying where disasters are most likely to occur and who is most vulnerable.
2. Monitoring & Early Warning
Goal: Detecting disasters as early as possible and issuing early warnings.
3. Damage Assessment
Goal: Quickly assessing the impact of a disaster.
4. Emergency Response
Goal: Rapidly deploying resources for disaster relief after a disaster occurs.
5. Recovery & Adaptation
Goal: Restoring social systems and reducing future risks.

Disaster research data presents several typical challenges:
1. Multi-source data
2. Spatiotemporal heterogeneity
3. Data scarcity
4. Noisy data

Model Challenges
1. Multimodal Integration
2. Multi-scale Problem
3. Generalization
4. Explainability

## What is GenAI? What are the common types/applications of GenAI, and why are they potentially powerful in disaster resilience research and disaster management (think about the monitoring, mapping, modeling, management, and mitigation framework)? How can GenAI/GenGeoAI support tasks to improve disaster resilience? 
First, we need to understand that the main tasks of traditional AI are classification, prediction, and detection. Generative AI (GenAI) is a type of AI technology that can learn data distributions and generate new content. Its core capability is naturally generating new content, including but not limited to images, text, and video. Common techniques include Large Language Models (LLMs), Diffusion Models, and multimodal generative models such as vision-language models.

I believe GenAI has main characteristics, which are also summarized in Dr. Zhongzheng Tu's course: GenAI can generate more content (data); it has cross-modal capabilities (visual language capabilities; and reasoning, which can be used for explanation).
Main Types and Applications of GenAI. In real-world applications, GenAI can be broadly categorized into five types:

1. Text Generation: 
Automatic report generation, disaster information summarization, policy analysis, and emergency decision support.
Example: Automatically summarizing disaster information from social media.

2. Image Generation:
Models: GAN, Diffusion models
Applications: Disaster scenario simulation, data augmentation, virtual training data generation.
Example: Generating flood or fire scenarios for model training.

3. Multimodal Generation:
Image understanding + text interpretation and cross-modal reasoning.
Example:
Analyzing street view images and generating disaster damage descriptions.

4. Synthetic Data Generation:
Applications: Few-shot learning, data augmentation, simulating extreme events.
Example: Generating rare disaster data.

5. Simulation/World Models:
Applications: Disaster evolution simulation, urban system simulation, complex system prediction.
Example:
Simulating wildfire spread or flood propagation.

Disaster research typically involves five aspects: monitoring, mapping, modeling, management, and mitigation.
GenAI has potential in all of these areas.
1. Monitoring
GenAI can:
Automatically analyze satellite imagery
Automatically interpret the street view image
Automatically summarize social media

2. Mapping
GenAI can help:
Automatically generate disaster maps
Automatically identify damaged buildings
Automatically update geographic databases


3. Modeling
GenAI can:
Build complex system models
Simulate disaster propagation
Predict disaster impacts


4. Management
GenAI can assist in:
Emergency decision-making
Resource allocation
Risk communication

5. Mitigation
GenAI can help with:
Urban planning
Risk prediction
Climate adaptation

GenAI's key advantages in disaster research lie in 1) multimodal understanding capabilities, 2) few-shot learning capabilities, 3) automated knowledge generation, and 4) complex system simulation capabilities. My current research shows that GenAI supports three key tasks: disaster perception, disaster reasoning, and disaster diagnosis. This is also the core idea behind my multi-agent disaster system.

## Case studies (it is important to think about how each case study reflects/represents the potential of GenAI/GenGeoAI in supporting disaster resilience improvement tasks)

Case Study 1: Disaster Monitoring Using Social Media + LLM (Bing Zhou) 
During disasters, a vast amount of information spreads rapidly through social media. Generative artificial intelligence, especially large language models (LLMs), can automatically analyze and summarize this textual information, extracting the location, type, and extent of the disaster. For example, the model can identify flood or fire-related information from social media posts and generate real-time disaster summaries. This approach transforms dispersed social media information into a "social sensing system," thereby improving the speed and coverage of disaster monitoring.

Case Study 2: Disaster Mapping Using Remote Sensing Imagery or Street View + GenAI (Yifan Yang)
Rapidly assessing damage after a disaster is crucial for emergency response. Generative artificial intelligence can combine remote sensing imagery and computer vision models to automatically identify damaged buildings, flooded areas, or road disruptions, generating disaster loss maps. For example, by analyzing pre- and post-disaster satellite imagery, the model can detect changes and create a damage distribution map. This automated disaster mapping technology can significantly improve the efficiency of disaster assessment and provide vital spatial information support for the allocation of relief resources. The same approach can be used for street view imagery. We can generate street view images from remote sensing images and then perform ground sensing.

Case Study 3: Disaster Scenario Simulation Using Generative Models (Debayan Mandal)
Generative artificial intelligence can also be used to simulate different disaster scenarios, thereby supporting disaster risk prediction. This can also be considered digital twins. For example, generative models can simulate flood diffusion processes under different rainfall intensities, or wildfire spread paths under different wind speeds. By generating multiple possible disaster scenarios, researchers can assess risk changes under different environmental conditions. This scenario simulation capability is of great significance for understanding the dynamic processes of disasters and developing disaster prevention strategies.


Case Study 4: GenAI Supporting Disaster Management Decisions (Ali Mostafavi or Zihui Ma)
During disaster emergency response, decision-makers need to quickly understand complex and constantly evolving information. Generative artificial intelligence, especially large language models, can integrate multi-source data from remote sensing imagery, social media, sensors, and official reports, and automatically generate disaster reports or decision recommendations. For example, the model can summarize the main problems in the affected area and propose rescue priorities or resource allocation plans. This technology helps managers understand the disaster situation more quickly, thereby improving the efficiency of emergency management.


## Existing challenges and future opportunities
While the application of GenAI/GenGeoAI to disaster resilience research and management holds immense potential, it also presents a series of challenges and significant development opportunities. Let's delve into some new aspects beyond the familiar ones.

First, significant challenges remain regarding data. Data is gold, data is oil. Disaster data often suffers from multi-source heterogeneity, large differences in spatiotemporal resolution, and data gaps. For example, remote sensing imagery, street view images, social media information, and sensor data vary significantly in format, quality, and update frequency, making multimodal data fusion difficult. Furthermore, some disaster events are low-frequency but high-impact, resulting in limited data samples available for model training, thus affecting the stability and generalization ability of the generated models. Data uncertainty and data quality have a significant impact on the results. My thinking is to become a researcher who creates comprehensive data. We should avoid generating one type of data from another, as this has a series of subsequent drawbacks. Can we simulate the entire process, creating a world model? In this way, all the scientific phenomena within the data are accessible.

Second, model reliability and generalization ability remain key issues. Generative models can generate misinformation or "hallucinations," and in high-risk decision-making environments like disaster management, this uncertainty can have serious consequences. Furthermore, many models are trained on data specific to a particular region or disaster type, thus limiting their applicability across different regions or disaster scenarios. Therefore, I've been considering the current level of zero-shot models, which is why I created agent4disaster—to examine the most basic capabilities of existing models.

Third, interpretability and decision-making trust are also significant challenges. Disaster management involves multiple stakeholders, including governments, emergency agencies, and the public; therefore, model outputs not only need to be accurate but also explainable in their reasoning. If a model cannot clearly explain the basis of its predictions or recommendations, decision-makers may find it difficult to trust or adopt these technologies. Humans naturally distrust non-human content, especially AI capabilities, and there is currently anxiety surrounding AI. This will inevitably lead to a large amount of content attacking AI, even if AI makes fewer mistakes than humans, because when it does, the responsibility is difficult to assess.

In addition, ethical and data governance issues also need attention. For example, social media data may involve privacy issues, and content generated by generative models may also pose a risk of misleading information. Therefore, applying GenAI in disaster research requires establishing a transparent and responsible data governance framework. This is where mutual visibility comes in, as we discussed earlier. I believe that mutual visibility mechanisms can address privacy issues to some extent.

GenAI, or AI in general, currently has two main paths: one is the general model, the world model—a large model that brute-forces solutions to all problems; embedding is a very good example, and there are increasingly more papers on it. The other is the agent—small and specialized, solving each small problem with capabilities far exceeding those of humans and existing models.

Overall, AI is disrupting everything, and we need to use AI as quickly as possible, research AI, and understand the essence of problems. We should boldly raise questions and then use engineer-like thinking to iterate rapidly.



## What is GeoAI?
GeoAI is a very complex concept, and we can interpret it from multiple perspectives. The difficulty lies in the fact that this interdisciplinary concept is hard to break down clearly. 

Why do we need to interpret it? Because whenever we propose a new concept, such as Responsible GeoAI or Fiduciary GeoAI, we need to first explain what GeoAI is. Before attempting to explain GeoAI, there are a few questions. First, what is the difference between GeoAI and AI for GEO-related Science? Considering other fields like biology, physics, and chemistry—hard sciences—we rarely hear it named BioAI, PhyAI, or ChemAI. It's more often called AI for Science. The core difference is: AI for Geo = AI as a tool to solve geospatial science problems. GeoAI = a new methodological system formed by the integration of AI and geospatial science. Therefore, my current research is more focused on AI4Science, specifically due to the breadth and inclusiveness of the GeoAI concept. My research can also be considered a part of GeoAI. GeoAI focuses on, but is not limited to, spatial autocorrelation, spatial heterogeneity, spatiotemporal processes, geographic scale, and proximity relationships—these are theoretical structures unique to geography. However, this is also a part that my current research lacks.

Therefore, if I had to summarize my current research, it would be Autonomous/Responsible/Fiduciary AI for/in disaster assessment. I consider disaster assessment to be part of geographical research. Disaster assessment uses computational tools to abstract complex information and simplify it to geographic information suitable for mapping.

Therefore, I'm also thinking about my future, even a ten-year research plan. I believe that using AI as a tool, AI4science, might be a research direction I excel at, and also an extension of my current path. AI4geography problems can always be studied, and can also be considered as the research content of geoAI. However, this type of research is always limited by AI. Similar to AI scientists discovering better models or algorithms, I apply them to my field. I'm more like an applied scientist, which is also my current role. Considering the special nature of geographical data, we can always publish papers in this way, although the impact of their work is limited. Secondly, there's cartography. Maps are one of the most special products with geographical characteristics. AI + mapping will involve a lot of engineering and ethical issues, which I'm very interested in. How to define the next generation of AI + cartography, and how to conduct entirely new research beyond AR, VR, and other technologies. Robotic cartography will change the role of cartographers in the future. But how humans interact with maps is also a very good question. Human-computer interaction in maps also requires geographical thinking. Just like Apple's products are superior to most brands, there are actually many research questions to consider. 

Finally, there's process modeling, which can also be understood as spatiotemporal intelligence, world models, and digital twins. I really like the concept of spatiotemporal intelligence because, in my view, time + space equals geography. My current research doesn't fully utilize the characteristics of time, even though we can consider pre- and post-disaster periods as spatiotemporal. Remote sensing is one of the best research subjects for spatiotemporal intelligence. I believe the greatest significance of spatiotemporal intelligence and world models lies in attempting to solve the problems of missing data and uncertainty. If we can continuously simulate the entire process of an event, then we can naturally discover its correlations and predict the future. Taking remote sensing-generated street-view as an example, if we use a world model to simulate the entire process of a hurricane's disaster, then we only need to capture remote sensing images and street-view images from different perspectives. The problem of missing data no longer exists; only angles are needed. Therefore, video generation is currently a path to solve this problem. I've also seen Dr. Wenwen Li use video models to predict wildfire planning. Similarly, I think audio models may also attempt to address seismic waves. Spatiotemporal intelligence is currently the most exciting research topic for me.


Returning to GeoAI, the mainstream explanations currently include Esri's explanation, the GeoAI tool developed by Dr. Qiusheng Wu, and Dr. Song Gao's manual explanation. GeoAI usually refers to Geospatial Artificial Intelligence. The core understanding is not as simple as "using AI on maps," but rather truly combining AI's learning ability with the spatial thinking of geography/GIScience, enabling machines to handle questions such as "where is it, why is it there, what are the nearby relationships, and how will it change over time."

Therefore, I prefer to understand GeoAI as having three layers. We can be considered GeoAI as long as we make contributions at any of these three levels.

The first layer: The data layer.

GeoAI deals with geospatial data, such as remote sensing imagery, street view imagery, trajectories, POIs, road networks, topography, meteorology, social media, population, and socioeconomic data. This data is often multi-source and heterogeneous, and it includes coordinates, time, and scale. A key value of GeoAI is that it puts this originally scattered data into a unified spatial framework for learning.

The second layer: The methodology layer.

GeoAI uses machine learning, deep learning, graph neural networks, spatiotemporal prediction, generative models, and visual language models, but the focus is on "spatialization." For example, remote sensing feature recognition, flood/fire detection, traffic prediction, site selection optimization, urban functional zone identification, and environmental exposure estimation are not merely simple classifications; rather, they enable the model to understand spatial structure and spatiotemporal processes.

The third layer: The science and decision-making layer.

Truly mature GeoAI not only achieves high accuracy but also supports geographic knowledge discovery and real-world decision-making, including disaster response, urban governance, ecological monitoring, public health, and infrastructure planning. Recent papers have also emphasized that GeoAI should not only focus on "task-oriented benchmarks" in the future, but should move towards stronger cross-modal reasoning, scientific discovery, interpretability, and ethical governance.


## 读书笔记（真金）
用发展的眼光看问题，这是一份终身职业，一份与你的一切不能分割的工作，有意义的失败远远比无意义的成果的有价值。狠狠地操练自己，你越强，找到你的观众越多。而不是你能讨好的人越多，你的观众越多。炸场是副产品，正如名利也是副产品。人是目的，不是手段。--《李诞脱口秀工作手册》

好好活就是做有意义的事，做有意义的事，就是好好活。
早熟的人吧，通常都晚熟。骄傲的人又很性急。
想要和得到，中间还有两个字，那就是要做到，你只有做到，才能得到。--《士兵突击》

竞技体育唯一的意义就是赢，因为每一个队都有勇气，热情和热爱。正如张艺兴在极限挑战说的一样，只有赢，游戏才好玩，才爽。剩下的一切都是安慰的借口罢了。--《观u23亚洲杯决赛有感》

古人之观于天地、山川、草木、虫鱼、鸟兽，往往有得，以其求思之深而无不在也。夫夷以近，则游者众；险以远，则至者少。而世之奇伟、瑰怪，非常之观，常在于险远，而人之所罕至焉，故非有志者不能至也。有志矣，不随以止也，然力不足者，亦不能至也。有志与力，而又不随以怠，至于幽暗昏惑而无物以相之，亦不能至也。然力足以至焉，于人为可讥，而在己为有悔；尽吾志也而不能至者，可以无悔矣，其孰能讥之乎？此余之所得也！--《游褒禅山记》

“我心中有一团火焰，它离我很近，我却摸不到；
死都不怕，就怕不安逸；
命都不要，就要安逸。
就这毛病，多少年来这是个被人钉死了的死穴。” --《我的团长我的团》

死都不怕，就怕不安逸，命都不要，就要安逸，就这毛病。多少年来这是个被人钉死了的死穴，一打一个准儿。--评论：今日割五城，明日割十城，然后得一夕安寝，起而四视，而秦兵又至矣《六国论》
--评论：“后人哀之而不鉴之，亦使后人而复哀后人也”《过秦论》--太阳底下并没有新鲜的事情

我想让事情是它本来该有的那个样子。--龙文章--《我的团长我的团》--致敬理想主义！

害怕并不代表没有勇气，真正的行动才是最重要的。一个人究竟是英雄还是懦夫，由行动决定。
领导力是一种能让别人追随你的能力，即使别人只是出于好奇。
视角的不同会令世界上所有重大事件的意义彻底发生改变，这令我惊叹不已。--《创业维艰》

如今回头看，这段生活对我而言，不啻为一种幸运。我在监狱中学会了乐观。在那以前，我一直以为自己生活在社会最底层。经历过无可比拟的绝望。但是在狱中，我懂得了所谓悲观与乐观都是相对的。--李明博

生活是属于每个人自己的感受，不属于任何别人的看法。--余华

我现在正在做的事情是对的吗？如果是错误的，我有勇气立刻停止吗？--段永平投资问答录

建立停止清单，本质上是一种通过“做减法”来聚焦的智慧。人的精力和资源是有限的。--段永平投资问答录

本分不是一种束缚，而是一种保护。它像是一道防火墙，将那些致命的风险、诱惑和错误决策隔绝在外。--段永平投资问答录

段永平对国内的情况非常了解，他觉得中国人敢于打拼，最大的优点就是勤劳朴实，但在打拼的过程中，他们可能会将精力全部投入工作，忽略了对生活的享受。当支持人问他希望给年轻人什么样的忠告的时候，他想了想，这样说道“如果一定要说，那就是享受生活，这是人来到这个世界上的目的。”--段永平投资问答录

怀有平常心的段永平，敏锐地意识到新时代的企业家和投资者可以有理想，也可以有追求，但更应该学会把握现实。毕竟理想主义者是走不远的，因为这样的人往往好高骛远，同样，那些纯粹的现实主义者很难将业务做大，因为这种人只看重眼前的利益，没有大格局和战略目光。一个出色的企业家应该是将现实主义与理想主义的有机结合，能够以平常心看待发生的事，能够依据事物的本来面目去做事，不违背规律和现实。--段永平投资问答录

互见性强调双向透明的责任制。透明性必须是双向的，作为一个“透明人”，我必须能够了解所有搜集我的信息并且观察我的机构，知道我自己的评分，还要有申诉的途径。他们能看到我，我也能看到他们。同样，责任必须是双向的。如果我不同意，觉得不公平或者系统出错，那我有权进行申诉。如果这一切完全是单方面的，我不会接受。它必须在某种程度上具有对称性。例如，如果对机构好处过多，对个人则不够，就会出现问题。--2049，未来10000天的可能。

在镜像世界中，互见性至关重要，我们必须确保搜集信息的系统自身的行为是公开且透明的。申诉和举证的权利也很重要。镜像世界是一个万物互联的世界，一旦遇到纠纷，需要有机制能调用所有记录个人行为的数据。举个例子，我走过了一条黑暗小巷，如果那里停着车，车载传感器搜集了我的行为数据，我就应该有权获取这些数据。我们需要一种机制，以便在出现纠纷的时候，能够调用所有搜集的信息，重现实际发生的情况。最后，为了加深互见性，还需要有两项保障性举措，一是设立隐私区，二是建立合理的上诉机制。--2049，未来10000天的可能。

“透明”的世界并不是说完全没有隐私，每个人都可以要求建立自己的隐私区。例如，智能手机时代的“不插电”运动，或者说断网，但大多数人可能不会选择这种方式；另一种更可行的选择是，信息搜集的结果只保存在本地，从不与外界共享，并且有明确的协议对此进行规定。人们也可以在公共空间设定专门的区域，在这些区域中不会进行任何信息搜集，比如一个不搜集任何信息的公园。就像在公共浴室或更衣室中不能使用手机一样，当你进入这样的区域时，你要摘下智能眼镜，完全退出镜像世界。--2049，未来10000天的可能。

所以在未来的镜像世界中，大多数情况下每个人都是“透明人”，随时随地被搜集信息。他们之所以会选择允许个人信息被搜集，是因为他们信任这个镜像世界，相信这是一个有互见性的世界，谁在搜集什么信息完全公开透明，每个人都有权利访问关于自己的任何信息，特别是在涉及法律问题时。每个人都有公开透明的申诉途径，系统必须有纠错机制。此外，这将涉及大多数人在透明与隐私保护之间的权衡。所以这一过程是渐进的，只有当大多数人从透明的社会中获得更多定制化的服务和福利时，他们才会选择让渡大部分隐私权。--2049，未来10000天的可能。

观察富人现在在做什么是我预测未来的一个重要方法。--2049，未来10000天的可能。

我经常说一句话：生产力是为机器人而设的，而不是为人类而设的。任何有生产力指标的工作，都不应该由人类而完成，未来尤其如此。而创新和创业的过程中充满了死胡同，充满了失败，都是非常低效的。而这恰恰是未来人类需要花更多时间去做的事情。--2049，未来10000天的可能。

众生平等，不是说众生都有一样的价值，而是说众生都一样没有价值。--《笑场》

一切有为法，如梦幻泡影。--《金刚经》
小胡：“...就算真变了帅哥，小北姑娘就算真喜欢上了，那喜欢的也只是个泡影而已啊。” 澈丹：“只要她喜欢，我做个泡影又怎么样呢？” --《笑场》

因果循环，报应不爽，说的不是你种了善因你就要得善果，种了恶因你就得恶果。种了善因，一定会有善果，只是善果不一定会报在自己身上，恶因也是一样。为了善果才种的善因，还叫善因吗？众生皆苦，诸法无常，好人也是众生，也是无常。一个人死了，就是死了，没有因果好说的。--《笑场》

菩提本无树，明镜亦非台。本来无一物，何处惹尘埃！--菩提偈

炮弹打不下春苗般的生机
铁翼下的种子，徒生些抗力，应声站起来大时代的战士
高塔般矗立在我们的土地
什么力也瞬灭不了火炭般的眼睛
什么声也遮蔽不住愤怒的吼声
烟火里孕育着复兴的幼芽
生存要在死里来争取
鲜血培养起自由之花
我们要在暗夜，竖立火炬
--小书虫

凡所有相皆是虚妄，若见诸相非相，即见如来。--金刚经

过去心不可得，现在心不可得，未来心不可得。--金刚经

一切有为法，如梦幻泡影。如露亦如电，应作如是观。--金刚经

天下事有难易乎？为之，则难者亦易矣；不为，则易者亦难矣。人之为学有难易乎？学之，则难者亦易矣；不学，则易者亦难矣。--为学一首示子侄

蜀之鄙有二僧：其一贫，其一富。贫者语于富者曰：”吾欲之南海，何如？“ 富者曰：”子何恃而往？“曰：”吾一瓶一钵足矣。”富者曰：“吾数年来欲买舟而下，犹未能也。子何恃而往！”越明年，贫者自南海还，以告富者，富者有惭色。西蜀之去南海，不知几千里也，僧富者不能至而贫者至焉。人之立志，顾不如蜀鄙之僧哉？--为学一首示子侄

是故聪与敏，可恃而不可恃也；自恃其聪与敏而不学者，自败者也。昏与庸，可限而不可限也；不自限其昏与庸，而力学不倦者，自力者也。--为学一首示子侄

时间的线性是温柔的骗局。--李诞《冷场》

“那你呢，你在这整个过程中究竟扮演什么角色。”
“场所吧，我是事情发生的场所。”--李诞《冷场》

我依旧发问我依然作答，我热爱我作为场所身上发生的事吗或者憎恨，热爱与憎恨是男友的情绪我多是接受，我可曾主动做过什么呢，维持场所稳定，我真的做好告别的准备了嘛随时，随时就像当初做好了登场的准备，我惧怕什么，我惧怕骗过了自己，我是否虚伪，我不虚伪，我会为今天面对鲸流的海说的话后悔吗，我不后悔不论面对什么我愿意再说一次只怕内容有变，我终于得到了坚实的心吗今天，今天我终于得到了坚实的心直至永远，我终于相信时间了吗谈到今天和永远，对不起，我始终不相信时间。“始终”不该是一个词，该是一个字，时间的线性是温柔的骗局。--李诞《冷场》

我的犹豫是宇宙的犹豫。墙上渗出海水，鲸始终未能将我吞入腹中。--李诞《冷场》
