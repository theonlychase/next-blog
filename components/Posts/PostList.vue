<template>
    <section class="post-list">
        <PostPreview 
            id="1"
            thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg"
            title="Hello"
            previewText="Preview Text"
        />
    </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
