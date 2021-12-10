### Hi there, I'm Sabiqul Haque Susmoy 👋

[Twitter Follow](https://img.shields.io/twitter/follow/sh_susmoy?color=1DA1F2&logo=twitter&style=for-the-badge)

## I'm a Software Engineer, Business Intelligence Professional.

<!--- 🔭 I just launched my first course: [Become A VS Code SuperHero!][course]!-->
- 🌱 I’m currently developing <b>Restful Web API</b> using <b>ASP.NET Core</b> ,<b> Web Application using .NET Core</b> and <b>Android Application following MVVM</b>
- 🏁 Problem Solving (Python)
- 👯 I’m looking to collaborate with my team members
- 🥅 2021 Goals: Data Warehouse implementation(SAP BW/4HANA) & Achieve Intermediate level on Web API Development
- ⚡ Fun fact: I love to travel and hangout with my friends

<!---### Connect with me:

[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin] !-->

<br/>

<div class="chart-wrap">
  <h2 class="title">HTML Bar Graph Example Using Flexbox</h2>
  <div class="grid horizontal">
  <div class="bar" style="--bar-value:85%;" data-name="Your Blog" title="Your Blog 85%"></div>
        <div class="bar" style="--bar-value:23%;" data-name="Medium" title="Medium 23%"></div>
       <div class="bar" style="--bar-value:7%;" data-name="Tumblr" title="Tumblr 7%"></div>
        <div class="bar" style="--bar-value:38%;" data-name="Facebook" title="Facebook 38%"></div>
        <div class="bar" style="--bar-value:35%;" data-name="YouTube" title="YouTube 35%"></div>
        <div class="bar" style="--bar-value:30%;" data-name="LinkedIn" title="LinkedIn 30%"></div>
        <div class="bar" style="--bar-value:5%;" data-name="Twitter" title="Twitter 5%"></div>
        <div class="bar" style="--bar-value:20%;" data-name="Other" title="Other 20%"></div>    
  </div>
</div>

@width:650px;
@height:600px;
@bar-size:45px;
@bar-color:#F16335;
@bar-rounded: 3px;

@grid-color:#aaa;

.chart-wrap{
  width: @width;
  height: @height;
  font-family:sans-serif;
  
  .title {
    text-align:center; 
  }
}

.grid{
  width:100%;
  height:100%;
  display:flex;
  flex-direction:row;
  justify-content:center;
  border-bottom:2px solid @grid-color;
  background:repeating-linear-gradient(0deg,transparent,transparent 19.5%,fadeout(@grid-color,30%) 20%);
  
  .bar {
    background-color:@bar-color;
    width:@bar-size;
    height: var(--bar-value);
    align-self:flex-end;
    margin:0 auto;
    border-radius:@bar-rounded @bar-rounded 0 0;
    position:relative;
    
    &.bar:hover{
      opacity:0.7;
    }
    
    &::after{
      content:attr(data-name);
      top:-3em;
      padding:10px;
      display:inline-block;
      white-space:nowrap;
      position:absolute;
      transform:rotate(-45deg);
    }
  }
  
  &.horizontal{
    flex-direction:column;
    border-bottom:none;
    border-left:2px solid @grid-color;
  background:repeating-linear-gradient(90deg,transparent,transparent 19.5%,fadeout(@grid-color,30%) 20%);
    .bar{
      height:@bar-size;
      width: var(--bar-value);
      align-self:flex-start;
      margin:auto 0 auto 0;
      border-radius:0 @bar-rounded @bar-rounded 0;
      
      &::after{
        top:initial;
        left:100%;
        padding:0 10px;
        display:inline-block;
        white-space:nowrap;
        position:absolute;
        transform:rotate(0deg);
        line-height:@bar-size;
      }      
    }
  }
}

<br /> 

### Languages and Tools:

<img align="left" alt="Python" width="26px" src="https://github.com/mshsusmoy/image_source/blob/main/python-seeklogo.com.svg" />
<img align="left" alt="Android Studio" width="30px" src="https://github.com/mshsusmoy/image_source/blob/main/Untitled-10.png" />
<img align="left" alt=".NET CORE" width="30px" src="https://github.com/dotnet/docs/blob/cb475ed45f881e9462e34764480d3b0ebce85e91/docs/images/hub/netcore.svg"/>
<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />
<img align="left" alt="PowerBI" width="26px" src="https://github.com/mshsusmoy/image_source/blob/main/powerbi.svg" />
<img align="left" alt="SAP Analytics Cloud" width="36px" src="https://github.com/mshsusmoy/image_source/blob/main/sap-logo-svg.svg" />
<img align="left" alt="MS SQL SERVER" width="50px" height="30px" src="https://github.com/mshsusmoy/image_source/blob/main/microsoft-sql-server-seeklogo.com.svg" />
<img align="left" alt="Oracle" width="50px" src="https://github.com/mshsusmoy/image_source/blob/main/oracle-seeklogo.com.svg" />
<img align="left" alt="GitHub" width="26px" src="https://github.com/mshsusmoy/image_source/blob/main/GitHub-Mark-Light-120px-plus.png" />
<img align="left" alt="JavaScript" width="26px" src="https://github.com/mshsusmoy/image_source/blob/main/javascript-js-seeklogo.com.svg" />
<br />
<br />


[twitter]: shorturl.at/wzWY7
[linkedin]: shorturl.at/ryKZ2
