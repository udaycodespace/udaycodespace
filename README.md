<div align="center">

<pre>
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│                          HI 👋, I'M SOMAPURAM UDAY                         │
│                                                                            │
│              Full-Stack Developer • Open Source Contributor                │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
</pre>

</div>

```console
uday@github:~$ ./whoami

==============================================================
                 DEVELOPER PROFILE LOADED
==============================================================

USER          : Somapuram Uday
ROLE          : Full-Stack Developer
LOCATION      : India
STATUS        : ONLINE

LAST UPDATE   : 30 Jun 2026
NEXT UPDATE   : 30 Jul 2026

CURRENT GOAL  : Rebuild GitHub Portfolio
TARGET DATE   : 31 Jul 2026

==============================================================
[0x01] ACTIVE PROCESSES
--------------------------------------------------------------

 PID    PROCESS                              STATUS
──────────────────────────────────────────────────────────────
1001    Full-Stack Development               RUNNING
1002    GitHub Portfolio Refresh             RUNNING
1003    Repository Reorganization            RUNNING
1004    Documentation Rewrite                RUNNING
1005    Microsoft Azure                      LEARNING
1006    Cloud Technologies                   LEARNING
1007    Open Source Contributions            ACTIVE

==============================================================
[0x02] CURRENT FOCUS
--------------------------------------------------------------

 > Reorganizing repositories
 > Improving project documentation
 > Learning Microsoft Azure
 > Learning cloud technologies
 > Contributing to open source
 > Building software that solves real-world problems

==============================================================
```

## Workflow

```mermaid
stateDiagram-v2
    [*] --> Repository_Reorganization
    Repository_Reorganization --> Documentation_Rewrite
    Documentation_Rewrite --> GitHub_Portfolio_Refresh
    GitHub_Portfolio_Refresh --> Ship_New_Projects
    Ship_New_Projects --> Open_Source_Contributions
    Open_Source_Contributions --> Microsoft_Azure
    Microsoft_Azure --> Cloud_Technologies
```

## Portfolio Refresh

```mermaid
gitGraph
    commit id: "30 Jun Snapshot"

    branch portfolio-refresh
    checkout portfolio-refresh
    commit id: "Repository Reorganization"
    commit id: "Documentation Rewrite"
    commit id: "README Cleanup"

    branch learning
    checkout learning
    commit id: "Microsoft Azure"
    commit id: "Cloud Technologies"

    checkout portfolio-refresh
    merge learning
    commit id: "Portfolio Refresh"
    commit id: "30 Jul Update"
    commit id: "31 Jul Target"
```

## Priorities

```mermaid
kanban
    In Progress
        GitHub Portfolio Refresh
        Repository Reorganization
        Documentation Rewrite

    Learning
        Microsoft Azure
        Cloud Technologies

    Active
        Full-Stack Development
        Open Source Contributions

    Next
        Ship New Projects
```

## Development Cycle

```mermaid
flowchart TD
    A["💡 Idea"]
        --> B["⚙️ Build"]
    B --> C["🧪 Test"]
    C -->|Pass| D["🚀 Ship"]
    C -->|Needs work| E["🔧 Improve"]
    E --> B
    D --> F["💬 Feedback"]
    F --> E
```

> *Currently cleaning up years of repositories because "I'll organize them later" eventually became a milestone.*
