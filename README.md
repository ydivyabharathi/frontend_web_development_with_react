# <center>Frontend Web Development With React</center>

## Configuration
> * npm init
> * npm install create-react-app
> * npx create-react-app confusion
> * cd confusion
> * npm start
> * npm install reactstrap
> * npm install bootstrap
> * npm install react-router-dom
> * npm install redux
> * npm install react-redux
> * npm install react-redux-form

## Rendering using `ReactDOM`. see `index.js`
    ReactDOM.render(<App />, document.getElementById('root'));

## Introduction to JSX

    const element = (
        <h1 classname='greeting'>
            Hello React
        </h1>
    );

    ===

    const element = React.createElement (
        'h1'
        {className:'greeting'},
        'Hello React'
    );

    ===

    const element = {
        type: 'h1'
        props: {
            className: 'greeting',
            children: 'Hello react'
        }
    }

## state in component
> * Each component can store its own local information in "state"

## React Component Lifecycle
> * Stages
>> * Mountung
>> * Updating
>> * Unmounting
> * Mounting Lifecycle Methods
>> * constructor()
>> * render
>> * componentDidMount()
> * Updating Lifecycle Methods
>> * getDerivedStateFromProps()
>> * shouldComponentUpdate()
>> * render()
>> * fetSnapshotBeforeUpdate()
>> * componentDidUpdate()

## Assignment-1
> * created a component
>> * `src/components/MenuComponents.js`
>> * created Reactstrap Media elements
> * imported the component to App.js 
> * imported App.js to index.js
> * removed App className
> * removed App.css contents

## Assignment-2
> * converted media elements to card elements
> * added onclick() eventListener to the card item

