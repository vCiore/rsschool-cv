# Valentina Ciorescu
Contacts: vciorescu@yahoo.com

With 13 years of experience as a math and coding teacher, I have dedicated my career to fostering a deep understanding of complex concepts and nurturing the next generation of tech-savvy professionals.
Over the last years, I transitioned into the dynamic field of full-stack development, combining my educational expertise with hands-on experience in modern web technologies.

**Key Highlights:**
- Extensive teaching experience in mathematics and coding, developing curricula that engage and challenge students. 
- Strong skills in JavaScript, with a deep understanding of modern development practices and tools.

I am passionate about leveraging my dual expertise in education and development to build innovative solutions that enhance learning experiences and drive technological advancement. My goal is to continue growing as a full-stack developer, contributing to projects that make a meaningful impact.

Let’s connect if you are looking for a professional who is passionate about education and technology, driven by a desire to create impactful digital experiences, and committed to continuous learning and improvement.
```
const pivotIndex = function(nums) {
   let totalSum = 0
   let sum = 0;
   for ( let i = 0; i < nums.length; i++) {
    totalSum += nums[i]
   }
   for (let i = 0; i < nums.length; i++) {
     if (sum === totalSum - sum - nums[i])  {
        return i
     }
     sum +=nums[i] 
   }
   return -1;
};
```