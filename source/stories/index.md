---
title: Story Recommendation List
description: TBA
---

<style>

.stories {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 0.5em;
}
.stories * {
     box-sizing: border-box;
}
.story {
    position: relative;
    border-radius: 0.25em;
    overflow: hidden;
}

.stories a:hover{
    color: white;
}

.story:hover img {
    transform: scale(1.05);
}
.story:hover .storyName {
    transform: translate(0, 0);
}
.story:hover .storyName .read {
    transform: translate(0, 0);
}
.storyName {
    transform: translate(0, 0);
}
.image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: 0.2s ease;
    margin: 0 !important;
}
.storyName {
    font-size: 0.9em;
    font-weight: 700;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    background: linear-gradient(to bottom, transparent 0, #000000a3 90%);
    color: #fff;
    position: absolute;
    padding: 5em 0.75em 0.75em;
    width: 100%;
    bottom: 0;
    left: 0;
    transition: 0.2s ease;
    transform: translate(0, 2.3em);
}
.storyName .read {
       margin-top: 0.25em;
       font-size: 0.85em;
       background: black;
       color: white;
       padding: 0.5em 1.25em;
       height: 2.25em;
       border-radius: 0.25em;
       width: 100%;
       text-align: center;
       transition: 0.2s ease;
       transform: translate(0, 1em);
   }
   .storyName .read:before {
       content: "Read";
   }

   .storyName .read.soon {
       opacity: 0.5;
       pointer-events: none;
       &:before {
           content: "Soon!";
       }
   }

   .storyName .read:not(.soon):hover {
       color: #f1c755;
   }
   @media only screen and (max-width: 600px) {
    .stories {
        grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
    }
}
</style>

## Introduction

In here you'll find a list of story recommendations for different parts of Ryuseitai. It will be expanded further as time goes on!

Click [here](/red_green/) for Midori and Chiaki's relationship!

## Spring
<div class="stories">
    <div class="story">
        <div class="image">
            <img
                src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b2/%28Ninpou%2C_Yuru-style%29_Midori_Takamine_Frameless.png"
                alt="Climax"
            />
        </div>
        <a href="https://310mc.github.io/climax" class="storyName" target="_blank">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b2/%28Ninpou%2C_Yuru-style%29_Midori_Takamine_Frameless.png"
                alt="Sweet Halloween"
            />
        </div>
        <a href="https://310mc.github.io/sweet_halloween" class="storyName" target="_blank">
            <span>Sweet Halloween</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b2/%28Ninpou%2C_Yuru-style%29_Midori_Takamine_Frameless.png"
                alt="School Festival 4"
            />
        </div>
        <a href="https://310mc.github.io/school_festival_4" class="storyName" target="_blank">
            <span>School Festival 4</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b2/%28Ninpou%2C_Yuru-style%29_Midori_Takamine_Frameless.png"
                alt="Orihime and Hikoboshi"
            />
        </div>
        <a href="https://310mc.github.io/orihime_and_hikoboshi" class="storyName" target="_blank">
            <span>Orihime and Hikoboshi</span>
            <span class="read"></span>
        </a>
    </div>
</div>
