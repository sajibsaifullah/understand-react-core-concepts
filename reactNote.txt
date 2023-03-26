==>JSX:
    - JavaScript XML
    - syntax extension for React JS
    - easier to read & write
    - gets transpiled to js with Babel. ( Transpiling is converting one higher level language to another higher level language)
    - return one <div></div> or <></>(fragment)
    - must need closing tag. ex. <img />
    - camelCase [exc. 'className', onClick]

==> Props: (drilling)
    - use props in React to pass data from one component to another (from a parent component to a child component)
    - unidirectional
    - can send all valid js

==> State:
    - build-in React object thai is used to contain data or information about the component
    - can change over time; whenever it changes, the component re-render
    - the change in state can happen as a response to user action or system-generated event.

======================================
==> State vs Props
    - state:
        - mutable & value can change as per requirement
        - set by parent component
        - is local , cannot be used in other component
    -props:
        - immutable, value can not change once assigned
        - send by event handler
        - allows child components to read values from parent component
========================================

==> Hooks:
    - allow function components to have access to state and other React features
    - useState
    - useEffect