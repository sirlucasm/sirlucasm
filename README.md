### Hello 👋

```
  
  router.post('/me/create', (req. res, next) => {
      user_params = {
          name: 'Lucas Matheus',
          email: 'lucasmatheus2021@gmail.com',
          age: 19
      };
      User.insert(user_params)
      .then(() => res.status(201).json({ message: 'User successfully created' }))
      .catch(error => res.status(500).json({ message: 'Not possible to save user' }));
  })

```

<br/> ReactJS, NodeJS, React Native PHP, HTML5, CSS3, Ruby, Python, Postgres, MYSQL

[![Linkedin Badge](https://img.shields.io/badge/-sirlucasm-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/sirlucasm//)](https://www.linkedin.com/in/sirlucasm/)
[![Gmail Badge](https://img.shields.io/badge/-lucasmatheus2021@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white)](https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin)

[![Instagram Badge](https://img.shields.io/badge/@sirlucasm-%23E4405F.svg?style=flat&logo=instagram&logoColor=white&link=https://www.instagram.com/cleitonnnnnn//)](https://www.instagram.com/sirlucasm/)

<!--
**sirlucasm/me** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
