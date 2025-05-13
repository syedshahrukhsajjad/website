Abstract / Introduction
TopicTalk is a web-based forum platform that allows users to create discussion topics, participate in conversations, and engage with a community of users on various topics of interest. The platform provides an interactive and collaborative environment for sharing ideas, asking questions, and connecting with like-minded individuals. 

Functional Requirements:

1)	User Authentication: Implement user authentication and authorization functionalities to allow users to sign up, sign in, and manage their profiles. Users can have different roles such as regular users, moderators, and administrator. Allow users to create profiles with bio, avatar, and other optional information. Profiles can display users' activity, posts, and contributions to the forum.
a)	A default “Admin” account shall already be available. 
b)	Whenever a new user registers, its default role shall be “Regular User”.
c)	Only “Admin” can promote or demote the role of a user to “Moderator” or back to “Regular User”. Hence, no option should be provided to be registered as a “Moderator”.
d)	There cannot be more than one “Admin”. But there can be multiple “Moderators”.
2)	Discussion Topics: Users can create new discussion topics or threads on specific subjects. Each topic can have multiple posts or replies from users.
3)	Categories and Tags: Organize discussion topics into categories and allow users to tag their posts with relevant keywords to improve searchability and categorization.
4)	Post Management: Enable users to create, edit, and delete their own posts. Moderators and administrator have additional capabilities to moderate posts, such as locking topics, deleting inappropriate content, or banning users.
5)	Rich Text Editor: Provide a rich text editor for composing posts with formatting options, embedded media (images, videos), and hyperlinks.
6)	User Interactions: Allow users to like, dislike, and comment on posts to engage in conversations and express their opinions.
7)	Search Functionality: Implement a search feature to allow users to find specific topics or posts based on keywords, authors, or categories.
8)	Notifications: Notify users about new replies, mentions, or activity on topics they are following via email or in-app notifications.
9)	Social Sharing: Integrate social sharing buttons to allow users to share interesting topics or posts on social media platforms.
10)	Gamification: Implement gamification elements such as badges, points, or levels to reward active participation and encourage user engagement.
11)	Mobile Responsiveness: Ensure the application is fully responsive and optimized for mobile devices to provide a seamless user experience across different screen sizes.

Tools:
1.	Frontend: HTML, CSS, JavaScript, and Bootstrap for building the user interface.
2.	Backend: PHP or Laravel for server-side scripting, and a database system like MySQL to store user data, posts, and other information.
