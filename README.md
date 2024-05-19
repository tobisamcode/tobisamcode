[![wakatime](https://wakatime.com/badge/user/b33b7a57-ee55-447b-a060-022b946b54d8.svg)](https://wakatime.com/@b33b7a57-ee55-447b-a060-022b946b54d8)

[![CodeTime Badge](https://img.shields.io/endpoint?style=social&color=222&url=https%3A%2F%2Fapi.codetime.dev%2Fshield%3Fid%3D25312%26project%3D%26in=0)](https://codetime.dev)

```ts 
interface Person {
  readonly name: string,
  readonly gender: "male" | "female",
  age?: number
}

interface Contact {
  email: string,
  twitter: string,
  linkedIn: string
}
  
interface Engineer extends Person, Contact {
  level?: string,
  languages: string[],
  stack: string[]
}

const tobi: Engineer = {
  name: "Tobi Adesokan",
  gender: "male",
  email: "samueloluwatobiloba48@gmail.com",
  twitter: "twitter.com/tobisam100",
  linkedIn: "linkedin.com/in/tobiadesokan/",
  languages: ["Python", "JavaScript", "Typescript", "Elixir"],
  stack: ["Reactjs", "Nextjs", "React Native", "Nodejs", "Express"] 
}

```
