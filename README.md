# mermaids

## FlowChart Left to Right

```mermaid
flowchart LR
    A ---> B
    B ---> C
    C ---> D
    D ---> E
    E ---> A
```


``` mermaid
flowchart LR
    WakeUp-- Brush Teeth -->B(EatBreakfast)
    EatBreakfast-->Go To College
    Exercise-->GoToWork
    GoToWork-->ReturnHome
```



## Flow Chart Top to Bottom


```mermaid
---
title: Flowchart
---
flowchart TB
    Christmas -- Get money -->B(Go shopping)
    B --> C{Let me think}
    C -- One --> D[Laptop] 
    C -- Two -->E[iPhone]
    C -- Three --> F[Car]
    style Christmas fill:red,stroke:white
    style B fill:green,stroke:white
    style C fill:green,stroke:white
```


## Pie Chart


``` mermaid
pie 
    title Pie Chart
    "Words" : 7
    "Voice Tone" : 38
    "Body Language" : 55
%%{init: { 'themeVariables': { 'pie1': 'red', 'pie2': 'yellow', 'pie3': 'blue'}}}%%   
```


## Mindmap


``` mermaid
mindmap
        A
            B
                C
            D
            E
                X
                Y
```


## Mindmap


``` mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```


## Timeline


```mermaid
timeline
    title History of Social Media Platform
    2002 : LinkedIn
    2004 : Facebook
         : Google
    2005 : Youtube
    2006 : Twitter
```

## XY Chart 


```mermaid
xychart-beta
    title "Revenue Chart"
    x-axis [January,February,March,April]
    y-axis "Revenue" 4000 --> 10000
    bar [5000, 6000, 7500, 10000]
    line [5000, 6000, 7500, 10000]
```
