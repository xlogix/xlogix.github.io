<template>
    <footer>
        <div class="container mx-auto py-4">
            <ul
                class="mx-auto p-4 max-w-sm lg:hidden flex items-center justify-between text-gray-500 dark:text-gray-400"
            >
                <li>
                    <a
                        href="mailto:abhishekuniyal09@gmail.com"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <envelope class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://github.com/xlogix"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <git-hub class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://twitter.com/abhispace97"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <twitter class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.linkedin.com/in/abhishek-uniyal/"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <linked-in class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.facebook.com/abhis.space/"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <facebook class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://medium.com/@abhishekuniyal"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <medium class="h-2/3 w-2/3" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://youtube.com/c/GypsyTheDj"
                        target="_blank"
                        rel="noreferrer"
                        class="h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1"
                    >
                        <you-tube class="h-2/3 w-2/3" />
                    </a>
                </li>
            </ul>
        </div>
    </footer>
</template>

<script>
import Envelope from '../Icons/Envelope.vue';
import Facebook from '../Icons/Facebook.vue';
import GitHub from '../Icons/GitHub.vue';
import LinkedIn from '../Icons/LinkedIn.vue';
import Medium from '../Icons/Medium.vue';
import Twitter from '../Icons/Twitter.vue';

export default {
    name: 'Footr',
    components: {
        Envelope,
        GitHub,
        Twitter,
        LinkedIn,
        Facebook,
        Medium
    }
};
</script>
