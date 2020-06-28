<template>
  <div class="application">
      <h1>Application</h1>
      <app-form /> // Step 1 to make app-form a child vue of application
  </div>
</template>

<script>
import AppForm from 'src/components/AppForm.vue' // Step 2 to make app-form a child component of application
export default {
    name : 'Application',
    components: {
        AppForm // Step 3 to make app-form a child component of application
    }
}
</script>
