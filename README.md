class Me {}

class About extends Me {
    getCurrentWorkplace() {
        return {
            workplace: {
                company: 'Rising Technologies',
                position: 'Software Engineer'
            }
        };
    }

    getDailyKnowledge() {
        return [
            'Javascript',
            'React',
            'Next',
            'Node',
            'Typescript',
            'Taiwindcss',
            'Material UI'
            'AWS'
            'TRPC'
            'T3 Stack'
        ];
    }

    getFutureGoal() {
        return 'To contribute to open source.';
    }
}
