<template>
  <div class="form">
    <h1>Hello World</h1>
    <form id="form" @submit="checkForm" action="https://vuejs.org/" method="post">
      <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="user_name" />
      </div>
      <div>
        <label for="mail">E-mail:</label>
        <input type="email" id="mail" name="user_mail" />
      </div>
      <div>
        <label for="msg">Date of Birth:</label>
        <input id="message" name="user_dob" />
      </div>
      <p>
        <input type="submit" value="Submit" required/>  
      </p>
    </form> 
  </div>
</template>

<script>
export default {
	name: 'Form'
};
</script>