# react-typescript-best-practices

React and Typescript best practices.
A work in progress ....

## Typescript

1. Always add return types. (1)
2. Interfaces Over Intersections. (1)
3. `extend` interfaces versus unions. (1)
4. Don't destructure the function signature. (2)
5. Use lodash's `defaultsDeep` to merge default props. (2)
6. Use sensible defaults. (2)
7. The number of props should be 0-2. (4, 5).

## React

1. Don't add return types. It's automatically inferred. (3)
2. Don't destructure the function signature. (2)
3. Use lodash's `defaultsDeep` to merge default props. (2)
4. Don't use `React.FC`. (3)
5. Use `ReactNode` type for `children`. (3)
6. Move helper functions outside the component. (4)
7. Destructure props and use only the destructured names. (4)
8. The number of props should be 0-2. (4, 5).
9. Avoid conditional rendering. (4)
10. Avoid nested ternary operators. (4)
11. Use reducers for state. (4, 6)
12. Stateless and stateful vs. container and presentational. (4)
13. Use absolute imports and module path aliases. (4, 7)
14. Don't rely on snapshot tests. (4)
15. Work against mock data and mock API. (8)
16. Avoid state that can be derived. Calc on the fly. (8)
17. Avoid render props. (4)

## Sources

1. [Microsoft Typescript Wiki](https://github.com/microsoft/TypeScript/wiki/Performance)
2. [TSX DX](https://github.com/osequi/test-tsx-dx-2)
3. [React TypeScript Cheatsheet](https://react-typescript-cheatsheet.netlify.app/)
4. [Tao of React](https://alexkondov.com/tao-of-react/)
5. [The Deno Manual](https://deno.land/manual)
6. [Zustand](https://github.com/pmndrs/zustand)
7. [The Next.js Manual](https://nextjs.org/docs/advanced-features/module-path-aliases)
8. [Lessons learned from 5 years in React.](https://www.dropbox.com/s/tsid5bnphznbvjv/Lessons%20learned%20from%205%20years%20in%20React.docx?dl=0)
