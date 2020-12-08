# react-scroll-up-btn



Source code at https://github.com/weianofsteel/react-scroll-up-button

## Installation

    npm install --save react-scroll-up-btn

or

    yarn add react-scroll-up-btn

## Usage

``` 
import React from 'react';
import ScrollUpButton from 'react-scroll-up-btn';

function Demo(){
    return(
        <React.Fragment>
            <div>
                <ScrollUpButton 
                    behavior={'smooth'}
                    IconSize={'5rem'}
                    appearCoordinate={1200}
                />    
            </div> 
        </React.Fragment>
    )
}

export default Demo;
```

## Props

|        Name        |        Type       |  Default  | 
|--------------------|-------------------|-----------|
|      behavior      |      'smooth'     |   'auto'  |  
|      IconSize      |  '?px' or '?rem'  |   '60px'  |           
|  appearCoordinate  |  number(scrollY)  |    1200   |                

