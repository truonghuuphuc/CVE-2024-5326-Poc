# CVE-2024-5326
CVE-2024-5326 Post Grid Gutenberg Blocks and WordPress Blog Plugin – PostX &lt;= 4.1.2 - Missing Authorization to Arbitrary Options Update

Description

The Post Grid Gutenberg Blocks and WordPress Blog Plugin – PostX plugin for WordPress is vulnerable to unauthorized modification of data due to a missing capability check on the 'postx_presets_callback' function in all versions up to, and including, 4.1.2. This makes it possible for authenticated attackers, with Contributor-level access and above, to change arbitrary options on affected sites. This can be used to enable new user registration and set the default role for new users to Administrator.

https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/ultimate-post/post-grid-gutenberg-blocks-and-wordpress-blog-plugin-postx-412-missing-authorization-to-arbitrary-options-update

User Contributor enable new user registration and set the default role for new users to Administrator.

Poc:

https://github.com/truonghuuphuc/CVE-2024-5326/assets/20487674/fca81a71-9812-4d0f-b48f-2db94e2c7347

