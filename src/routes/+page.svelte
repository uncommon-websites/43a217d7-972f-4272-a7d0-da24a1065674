<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Your expertise, infinitely scalable"
	subtitle="Transform your knowledge into an interactive digital mentor that provides personalized guidance to thousands while you focus on what matters most."
	imageSrc="/generated/image-a-serene-indoor-environment-with-a-sooth.webp"
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/masterclass.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kajabi.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/teachable.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/patreon.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Delphi creates interactive digital replicas of coaches and consultants, trained on their complete knowledge base to deliver personalized mentorship at scale. Whether through voice calls, video chat, or text, your digital mentor authentically mirrors your expertise and personality, guiding thousands of clients simultaneously. This means you can monetize your knowledge without trading hours for dollars, while your audience receives the personalized guidance they need, exactly when they need it."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Executive Coach",
			company: "Catalyst Coaching",
			quote:
				"I was spending 40 hours a week on one-on-one calls and turning away clients. My Delphi clone now handles 200+ personalized conversations monthly while I focus on my flagship programs. It's like hiring 10 versions of myself without the overhead.",
			image: "/generated/image-professional-confident-female-life-coach.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Business Consultant",
			company: "Thompson Advisory",
			quote:
				"My expertise was trapped in my calendar at $500 per hour. Delphi freed me to serve 15,000 followers with personalized guidance 24/7. I tripled my revenue while cutting my consulting hours by 60%. The ROI was immediate.",
			image: "/generated/image-professional-male-business-consultant-he.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Wellness Course Creator",
			company: "Mindful Living Academy",
			quote:
				"Student questions were overwhelming my inbox and delaying course launches. My digital mentor now provides instant, personalized support that sounds exactly like me. My completion rates jumped 45% and I launched two new programs this quarter.",
			image: "/generated/image-professional-female-wellness-expert-head.webp"
		}
	]}
/>

<Features
	title="Mentorship that scales infinitely"
	subtitle="Transform your expertise into an interactive digital mentor that delivers authentic, personalized guidance to thousands simultaneously."
	features={[
		{
			title: "Voice and video authenticity",
			description:
				"Your digital mentor speaks, responds, and engages through natural voice calls and video chat that authentically mirror your unique speaking style and personality."
		},
		{
			title: "Infinite personalization",
			description:
				"Deliver tailored guidance to thousands of individuals simultaneously, each receiving responses calibrated to their specific context and needs."
		},
		{
			title: "Knowledge continuity",
			description:
				"Preserve and scale your complete expertise so your wisdom remains accessible and actionable, transcending time and geographic boundaries."
		},
		{
			title: "Monetize without limits",
			description:
				"Generate revenue from your expertise 24/7 without trading hours for dollars, freeing you to focus on high-impact work that matters most."
		},
		{
			title: "Audience intelligence",
			description:
				"Understand patterns in the questions and challenges your audience faces, enabling you to refine your offerings and create more relevant content."
		},
		{
			title: "Seamless integration",
			description:
				"Deploy your digital mentor across existing platforms and workflows, meeting your audience where they already engage with your content."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop trading hours for dollars"
	subtitle="Your digital mentor launches in 48 hours"
	description="Join 847 coaches and consultants who scaled their expertise to thousands of clients without adding a single hour to their calendar. Your audience wants personalized guidance now, not when your calendar opens up three weeks from today."
	imageSrc="/generated/image-a-confident-professional-coach-sits-comf.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Build your digital mentor",
			variant: "primary"
		},
		{
			href: "/examples",
			label: "See it in action",
			variant: "secondary"
		}
	]}
/>
